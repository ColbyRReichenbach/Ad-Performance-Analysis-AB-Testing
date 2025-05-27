# A/B Testing for Enhanced Ad Campaign Performance

This repository details a comprehensive data analysis project focused on optimizing social media ad campaigns through rigorous A/B testing. The primary objective is to dissect ad performance, evaluate campaign effectiveness, and provide actionable, data-driven recommendations for strategic marketing improvements.

## Project Overview

This project analyzes ad campaign data from a fictitious company to identify key factors driving ad performance and conversion rates. The analysis encompasses several key stages:

* **Exploratory Data Analysis (EDA):** In-depth examination of the dataset, including descriptive statistics, outlier detection, and calculation of core performance metrics.
* **A/B Testing & Statistical Validation:** Systematic comparison of different ad creatives and campaign strategies, with results validated using appropriate statistical tests (e.g., t-tests) to determine significance.
* **Segmentation Analysis:** Utilization of Chi-Square tests to evaluate the impact of demographic and interest-based segmentation on conversion rates.
* **Marketing Funnel Analysis:** Identification of potential bottlenecks and areas for improvement within the customer journey, from initial impression to final conversion.
* **Key Insights & Strategic Recommendations:** Derivation of data-driven strategies designed to enhance campaign ROI and foster sustainable growth.

## Repository Structure

## Repository Structure

```bash
├── notebooks/
│   └── Final_Notebook.ipynb        # Full analysis with code
├── figures/                        # figures derived from notebooks - for use in reports
├── data/
│   └── conversion_data.csv         # Raw dataset
│   └── df_cleaned.csv              # Cleaned dataset
│       ├── from_notebook/          # Saved tables from analysis/tests
├── README.md                       # Project documentation
├── Summary_Report.md               # Executive summary with key insights
├── report.md                       # Detailed report with analysis
└── requirements.txt                # Required packages to run notebook
```

## Key Findings

* **Campaign 916** was identified as a top performer, achieving a significantly higher conversion rate of **14.16%** compared to other campaigns.
* Statistical analysis using **Chi-Square tests** indicated no significant differences in conversion rates across the evaluated demographic segments.
* **A/B tests confirmed that creative elements** (e.g., ad copy, visuals) play a crucial role in driving user engagement and conversion.
* Marketing funnel analysis revealed **major bottlenecks in the impressions-to-clicks stage (CTR)**, suggesting an area for focused optimization.

## Strategic Recommendations

Based on the analysis, the following strategies are recommended:

1.  **Implement Hybrid Campaign Strategies:** Combine high-impression campaigns with those demonstrating high conversion rates to balance reach and efficiency.
2.  **Optimize Ad Creatives for CTR:** Focus on iteratively improving Click-Through Rates through continuous A/B testing of headlines, visuals, and calls-to-action.
3.  **Strategic Budget Reallocation:** Prioritize investment in demonstrably top-performing campaigns, such as Campaign 916, to maximize ROI.
4.  **Establish a Culture of Continuous Testing:** Implement ongoing A/B and multivariate tests to adapt to changing market dynamics and ensure continuous performance improvement.

## Tools & Technologies

* **Python:** Utilized for data manipulation, statistical analysis, and visualization.
    * **Key Libraries:** Pandas, NumPy, SciPy (for statistical tests), Matplotlib, Seaborn.
* **Jupyter Notebooks:** For interactive data exploration, code development, and documentation of the analysis workflow.
* **Statistical Methods:** T-tests, Chi-Square tests, confidence interval calculations.

## Limitations of Traditional A/B Testing & The Next Step in Optimization

While this A/B testing analysis provided valuable insights into ad creative and campaign effectiveness, it also highlighted a common challenge in traditional A/B testing: **the opportunity cost associated with the exploration phase.** During testing, budget is inevitably allocated to underperforming variants while sufficient data is gathered to reach statistical significance. This can lead to wasted ad spend and slower optimization cycles.

This observation sparked an interest in exploring more dynamic and efficient methods for ad optimization that could reduce this exploratory cost and accelerate the identification of top-performing creatives.

To address this, I developed a subsequent project implementing a **Multi-Armed Bandit algorithm**. This advanced approach aims to automate real-time ad optimization and potentially maximize campaign ROI more effectively than traditional methods.

**Explore the advanced Multi-Armed Bandit Optimization project here:** [https://github.com/ColbyRReichenbach/Self-Optimizing-Ad-Campaign]

## Contact

* **Email:** colbyrreichenbach@gmail.com
* **LinkedIn:** [Profile](https://www.linkedin.com/in/colby-reichenbach)

Feel free to reach out for any inquiries or collaborations!
