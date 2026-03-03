# ABtest-Design
Web Analytics &amp; A/B Test Design (Conversion Rate Optimization)
## Project Goal
To diagnose a severe engagement issue where 75% of landing page visitors drop off without scrolling. 
The objective was to analyze user behavior metrics and design an A/B test to improve the scroll and conversion rates.

## Tools & Technologies
* **Exploratory Data Analysis (EDA):** Correlation analysis between session length, clicks, and scroll depth.
* **Business Frameworks:** ICE (Impact, Confidence, Ease) scoring for hypothesis prioritization.
* **Statistical Pre-analysis:** Sample size calculation, Minimum Detectable Effect (MDE), p-value, and statistical power simulations.

## The Process & Logic
1. **Problem Identification:** Discovered that the median session length was only 18 seconds, meaning users were landing, reading the hero section, clicking, and immediately leaving.
2. **Hypothesis Generation:** Used the ICE framework to score potential solutions. 
A 4-option desktop navigation menu ranked highest (Score: 27) as it removes the uncertainty of the current "Download Syllabus" button.
3. **Statistical Setup:**
   * **Baseline:** 25% scroll rate
   * **Target:** 35% scroll rate (a 40% relative uplift).
   * **Requirements:** Calculated that 160 visitors per variation were needed to detect the effect, achievable in ~10 days based on a traffic volume of 1,000 visitors/month.
   * **Simulated Evaluation:** A successful test run at these metrics yielded a 99% Confidence Level and 99.5% Observed Power.

## Key Business Insights
* **Desktop vs. Mobile Discrepancy:** Identified that the desktop scroll rate (16%) severely lagged behind the mobile scroll rate (31%), despite similar click rates.
* **The "False Success" Click:** Discovered an anomaly where sessions under 60 seconds had a 13% click rate but a 0% scroll rate. Users were clicking to download a file and leaving immediately, feeling no need to explore the page.
* **Paid Marketing Inefficiency:** Paid Ads performed no better than Organic or Direct traffic (all hovering around a 25% scroll rate and 9-10% click rate). More critically, Paid Ads brought in the highest volume of bounce sessions - **20%**  of users left within one minute without engaging. This strongly indicates that ad messaging is misaligned with the landing page content or targeting the wrong audience.
