# Flowstack A/B Test Analysis: Personalized Onboarding Impact

This repository contains the analysis of a simulated A/B test conducted to evaluate the effectiveness of a newly designed personalized onboarding experience for Flowstack, a freemium SaaS platform. Flowstack helps individuals and teams manage tasks, projects, and workflows, offering both a free version and a premium subscription.

## Project Overview

Despite attracting a large number of new users through the free plan, Flowstack faced two major challenges: low 14-day user retention and a small percentage of users upgrading to premium. To address these issues, a new personalized onboarding experience was introduced, designed to guide users through relevant features and offer a time-limited trial of premium tools.

This A/B test compared the existing onboarding (Group A - Control) with the new personalized experience (Group B - Treatment). The experiment evaluated key user engagement and monetization metrics, including:
* Retention rate
* Premium upgrade rate
* Average Revenue Per User (ARPU)
* Support ticket volume

## Key Findings

The analysis revealed several significant outcomes:
* Group B users showed significantly higher retention rates and upgrade rates than Group A.
* Paying users in Group B had a higher ARPU, suggesting increased revenue per customer.
* Industry analysis highlighted Tech and Finance as the highest revenue-generating sectors, particularly responsive to the new onboarding.
* Regional analysis revealed North America and Europe as core revenue drivers, with Asia showing strong growth potential.
* Although Group B generated slightly more support tickets, this may reflect increased feature exploration rather than a flaw in user experience.

## Conclusion & Recommendations

The personalized onboarding strategy demonstrates a clear positive impact on user engagement and monetization. Rather than solely focusing on increasing prices, Flowstack should aim to convert more users and explore tiered pricing strategies to maximize lifetime value across diverse customer segments.

## Project Limitations

While the results are promising, it's important to acknowledge the limitations of this project:
* The data used for the experiment was simulated and may not fully reflect real-world behavior.
* The analysis focused on short-term outcomes (e.g., 14-day retention), without evaluating long-term customer engagement or churn.
* No segmentation was applied based on user behavior, firmographics, or acquisition channel, which may limit strategic targeting.
* The rise in support tickets in Group B was not explored in depth in terms of operational cost implications or customer satisfaction.
* External factors such as seasonality, competitor actions, or marketing variations were not considered.

## Future Work

A follow-up analysis using real user data, longer observation windows, and deeper segmentation would help validate and refine the onboarding strategy, pricing models, and product roadmap.

## How to Run

To run this analysis locally:
1.  **Clone the repository:** (Once created on GitHub)
    ```bash
    git clone [https://github.com/YourUsername/flowstack-ab-test-analysis.git](https://github.com/YourUsername/flowstack-ab-test-analysis.git)
    cd flowstack-ab-test-analysis
    ```
2.  **Install dependencies:** Ensure you have Python installed. It's recommended to use a virtual environment.
    ```bash
    pip install pandas numpy matplotlib seaborn jupyter
    ```
3.  **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook "AB testing project.ipynb"
    ```
    This will open the notebook in your web browser, where you can run the cells and explore the analysis.







