# A-B-Testing-for-Website-Optimization
Objective: Design and analyze A/B tests for better user experience.  Task Deliverables:  Set up A/B tests for homepage design variations. Track metrics like bounce rate and conversion rate. Outcome: Identify designs that drive higher engagement. 📊 Data Source: Internee.pk website analytics (e.g., Google Analytics).

# A/B Testing Analysis: Internee.pk Homepage Optimization

## Project Overview
This project focuses on designing and analyzing an A/B test for the **Internee.pk** homepage. The goal was to test two different design variations to determine which layout effectively reduces the bounce rate and increases the conversion rate for internship registrations.

## The Hypothesis
* **Control (A):** The current homepage layout.
* **Variation (B):** A modified layout featuring a more prominent "Apply Now" button and a simplified navigation bar.
* **Prediction:** Variation B will result in a lower bounce rate and a higher conversion rate due to reduced cognitive load.

## Metrics Tracked
1. **Bounce Rate:** The percentage of users who leave the site after viewing only the homepage.
2. **Conversion Rate:** The percentage of users who clicked the "Apply Now" button or signed up.
3. **Average Session Duration:** How long users stay on the page.

## Tech Stack
* **Python (Pandas & Scipy):** For statistical data processing and T-Tests.
* **Matplotlib/Seaborn:** For visualizing performance differences.
* **Google Analytics (Simulation):** Data modeled after typical Internee.pk traffic patterns.

## Statistical Analysis
We used a **Two-Sample T-Test** to ensure the results were statistically significant ($p < 0.05$). 

| Metric | Control (A) | Variation (B) | Change |
| :--- | :--- | :--- | :--- |
| **Conversion Rate** | 12.5% | 15.2% | +21.6% |
| **Bounce Rate** | 45.0% | 38.5% | -14.4% |
