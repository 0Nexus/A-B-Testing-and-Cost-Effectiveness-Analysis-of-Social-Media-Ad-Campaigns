# A/B Testing and Cost-Effectiveness Analysis of Social Media Ad Campaigns

## Overview
This project analyzes an anonymized social media ad campaign dataset from an organization to:
1. Perform A/B testing to identify significant differences in conversion rates across various demographic groups.
2. Evaluate the cost-effectiveness of the campaigns by calculating the cost per conversion for each group.

Using statistical analysis and data visualization, this project demonstrates how to optimize ad spend by targeting the most effective demographic segments.

---

## Project Objectives
- **A/B Testing:** Test if there’s a statistically significant difference in conversion rates between different groups (e.g., gender, age).
- **Cost-Effectiveness:** Analyze and compare the cost per conversion across groups to identify the most cost-efficient segments.
  
## Data
The dataset consists of 1,143 observations and 11 variables, detailing information about ads, their audiences, and performance metrics such as:
- **Ad ID**: Unique identifier for each ad.
- **Campaign ID**: Identifiers for XYZ company and Facebook campaigns.
- **Audience Demographics**: Age, gender, and interest codes.
- **Impressions**: Number of times the ad was shown.
- **Clicks**: Number of clicks on the ad.
- **Spend**: The amount spent on each ad.
- **Conversions**: Total conversions and approved conversions (actual purchases).

---

## Methodology
### 1. A/B Testing
Hypothesis testing was conducted using a two-sample t-test to evaluate whether there is a significant difference in conversion rates between:
- Males vs. Females
- Other demographic groups (e.g., age or interests)

### 2. Cost-Effectiveness Analysis
The cost per conversion for each group was calculated as:

$Cost\ per\ Conversion = \frac{Total\ Spend}{Approved\ Conversions}$

This helped in identifying which demographic groups provided the best return on investment for the ad spend.

---

## Key Insights
- **Conversion Rate Comparison:** Ads shown to males had a higher conversion rate compared to females, and the difference was statistically significant.
- **Cost per Conversion:** Males also had a lower cost per conversion, making them a more cost-effective target group for future ad campaigns.
- **Visualizations:** Several plots were generated to support the analysis, including bar plots for conversion rates, box plots for conversions, and scatter plots showing the relationship between spend and conversions.

---

## Technologies Used
- **Python Libraries**: 
  - `pandas` for data manipulation
  - `scipy` for statistical analysis
  - `matplotlib` and `seaborn` for data visualization
- **Hypothesis Testing**: Two-sample t-test to compare conversion rates between groups.
- **Cost Analysis**: Cost per conversion calculations for cost-effectiveness evaluation.

---

## Visualizations
The following visualizations were generated to better explain the data and analysis:
- **Bar Plot** for conversion rates by demographic groups.
- **Box Plot** for distribution of approved conversions.
- **Scatter Plot** showing the relationship between spend and conversions.
- **Cumulative Line Plot** tracking cumulative spend vs. cumulative conversions.

---

## Conclusion
This project provides insights into how demographic factors impact the performance and cost-effectiveness of social media ads. By targeting the most effective audience segments, advertisers can maximize conversions and optimize ad spend. Future work could include testing additional variables like age groups or analyzing trends over time.

---

## Usage
To run the project locally:
1. Clone the repository.
```
git clone https://github.com/your-username/your-repo-name.git
```
2. Install the required libraries.
```
pip install -r requirements.txt
```
3. Run the Jupyter notebook to reproduce the analysis.

---

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

---

### Author
Abderramane Wassim Mehdaoui  
[LinkedIn](www.linkedin.com/in/abderrahmane-wassim-mehdaoui-91a239198) | [Email](abderrahmane.mehdaoui@city.ac.uk) | [GitHub](https://github.com/0Nexus)
