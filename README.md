# Marketing Budget Optimization using Multiple Linear Regression

## Project Overview

This project focuses on analyzing marketing spend across different advertising channels and understanding their impact on sales revenue using Multiple Linear Regression.

The objective is to help the company optimize its marketing budget by identifying the most effective advertising channels and recommending better budget allocation strategies.

The analysis includes:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Multiple Linear Regression modeling
* Model evaluation
* ROI and channel effectiveness analysis
* Budget optimization recommendations

---

# Business Problem

Companies invest heavily in multiple marketing channels such as:

* TV Advertising
* Radio Advertising
* Social Media Marketing
* Search Ads
* Influencer Marketing

However, businesses often struggle to determine:

* Which channel generates the highest sales impact
* Which channel provides the best return on investment
* Which channels are underperforming
* How future marketing budgets should be allocated efficiently

This project aims to solve these problems using data-driven regression analysis.

---

# Problem Type

This is a **Regression Problem** because:

* The target variable (Sales/Revenue) is continuous numerical data.
* The goal is to predict sales values based on marketing spend.

---

# Objective

The main objectives of this project are:

* Predict sales revenue using marketing spend data
* Identify the most impactful marketing channels
* Evaluate marketing efficiency using ROAS
* Recommend optimized marketing budget allocation
* Support business decision-making using analytics

---

# Dataset Information

The dataset contains marketing spending information across multiple channels and corresponding sales revenue.

## Features Used

### Independent Variables (Input Features)

* TV_Spend
* Radio_Spend
* SocialMedia_Spend
* SearchAds_Spend
* Influencer_Spend

### Dependent Variable (Target)

* Sales / Revenue

---

# Technologies and Libraries Used

## Programming Language

* Python

## Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# Project Workflow

## 1. Business Understanding

* Defined business objectives
* Identified regression problem
* Determined independent and dependent variables

---

## 2. Data Understanding and Cleaning

The following preprocessing steps were performed:

* Dataset overview
* Missing value analysis
* Duplicate value check
* Data type verification
* Summary statistics generation
* Outlier detection using boxplots

### Data Quality Summary

The dataset was generally clean and structured appropriately for regression modeling. Minimal preprocessing was required before analysis.

---

# Exploratory Data Analysis (EDA)

EDA was conducted to understand relationships between marketing channels and sales.

## Visualizations Included

* Distribution plots of marketing channels
* Sales distribution analysis
* Scatter plots:

  * TV vs Sales
  * Radio vs Sales
  * Social Media vs Sales
  * Search Ads vs Sales
  * Influencer Spend vs Sales
* Correlation heatmap

---

# Key EDA Insights

* Radio and Search Ads showed strong positive relationships with sales.
* TV advertising also contributed positively to revenue generation.
* Social Media and Influencer marketing demonstrated weaker direct relationships with sales.
* Correlation analysis helped identify the most influential channels.

---

# Model Building

A Multiple Linear Regression model was built using marketing spend channels as input variables and sales as the target variable.

## Steps Performed

* Feature selection
* Train-test split
* Model training
* Sales prediction
* Coefficient interpretation

---

# Multiple Linear Regression

The model estimates the relationship between marketing spend and sales using the equation:

Sales = \beta_0 + \beta_1(TV) + \beta_2(Radio) + \beta_3(SocialMedia) + \beta_4(SearchAds) + \beta_5(Influencer)

Where:

* β₀ = Intercept
* β₁ to β₅ = Channel coefficients

---

# Model Evaluation

The regression model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## Evaluation Interpretation

* Lower MAE and RMSE indicate better prediction accuracy.
* Higher R² Score indicates stronger explanatory power.
* The model successfully captured the relationship between marketing spend and sales.

---

# ROI and Channel Effectiveness Analysis

Marketing effectiveness was analyzed using:

* Revenue generated per channel
* Return on Ad Spend (ROAS)
* Relative channel impact
* Regression coefficients

---

# Budget Recommendations Based on Analysis

Based on the multiple linear regression model and the channel effectiveness analysis, the following budget recommendations were identified.

---

## 1. Channels That Should Receive More Budget

### Radio_Spend

Radio advertising demonstrated the highest efficiency with the strongest positive ROAS performance.

* Highest modeled ROAS
* Strong direct relationship with sales
* Efficient revenue generation per unit spend

Recommendation:

> Increase investment in Radio advertising because it delivers the strongest sales return relative to spending.

---

### SearchAds_Spend

Search Ads also showed high efficiency and strong contribution toward revenue generation.

Recommendation:

> Allocate additional budget to Search Ads because they effectively capture customer purchase intent and drive measurable sales growth.

---

### TV_Spend

TV advertising contributed positively to sales and remains valuable for broad customer reach and brand awareness.

Recommendation:

> Maintain or moderately increase TV spending while optimizing campaign targeting strategies.

---

# 2. Channels That Should Receive Less Budget

## Influencer_Spend

Influencer marketing showed the weakest direct contribution to sales generation.

Recommendation:

> Reduce or carefully optimize Influencer marketing expenditure because its direct sales efficiency appears relatively low.

---

## SocialMedia_Spend

Social Media marketing demonstrated weaker direct ROAS compared to Radio and Search Ads.

Recommendation:

> Reassess Social Media campaigns and optimize spending allocation before increasing future investment.

---

# 3. Channels Appearing Less Effective

The following channels appeared less effective in directly driving short-term sales:

* Influencer_Spend
* SocialMedia_Spend

However, these channels may still contribute indirectly through:

* Brand awareness
* Customer engagement
* Long-term customer relationships
* Audience retention

Therefore, they should not be considered entirely ineffective without additional long-term performance analysis.

---

# Additional Data That Would Improve the Analysis

The following additional data could significantly improve future modeling accuracy:

## Customer-Level Data

* Customer demographics
* Customer lifetime value (CLTV)
* Purchase behavior

## Market Data

* Competitor advertising spend
* Industry trends
* Seasonal demand patterns

## Campaign Metrics

* Click-through rates
* Engagement metrics
* Conversion rates
* Reach and impressions

## Attribution Data

* Multi-touch attribution analysis
* Customer journey tracking

---

# Risks to Consider Before Changing Budgets

Before implementing major budget changes, the company should consider the following risks:

## Brand Awareness Risk

Reducing spend on Social Media or Influencer campaigns may negatively impact:

* Brand visibility
* Customer engagement
* Long-term loyalty

---

## Diminishing Returns

Increasing spend on high-performing channels may eventually lead to reduced incremental returns.

---

## Market Dynamics

Marketing effectiveness may change over time due to:

* Consumer behavior shifts
* Competitor actions
* Economic conditions
* Platform algorithm changes

---

## Long-Term vs Short-Term Performance

Some channels may contribute more strongly to long-term brand growth rather than immediate sales.

---

## Model Limitations

The linear regression model assumes linear relationships and may not capture:

* Non-linear marketing effects
* Interaction between channels
* External market influences

---

#Business Recommendations

Based on the regression analysis, ROAS calculations, and channel effectiveness evaluation, the following strategic business recommendations are proposed for optimizing the company’s marketing budget.

##1. Increase Investment in High-Performing Channels
Radio Advertising

The analysis identified Radio_Spend as the most efficient marketing channel with the highest modeled ROAS.

Why Radio Should Receive More Budget
Strong positive relationship with sales
Highest return generated per unit of advertising spend
Consistent revenue contribution
Cost-effective customer reach
Strategic Recommendation

The company should gradually increase the Radio advertising budget while continuously monitoring campaign performance.

Expected Business Impact
Higher incremental sales
Improved marketing efficiency
Better revenue generation with lower acquisition costs

##2. Expand Search Advertising Campaigns
SearchAds_Spend

Search advertising demonstrated strong performance and high marketing efficiency.

Why Search Ads Are Valuable
Captures customers with high purchase intent
Generates measurable and trackable conversions
Produces strong direct impact on sales
Provides scalable digital growth opportunities
Strategic Recommendation

The company should:

Increase investment in Search Ads
Improve keyword targeting strategies
Focus on high-converting customer segments
Optimize bidding and conversion campaigns
Expected Business Impact
Increased online sales conversions
Higher customer acquisition efficiency
Better targeting accuracy

##3. Maintain and Optimize TV Advertising
TV_Spend

TV advertising showed positive contribution toward sales and remains important for brand visibility.

Why TV Still Matters
Broad audience reach
Strong brand awareness generation
Supports long-term customer recall
Enhances overall campaign visibility
Strategic Recommendation

Rather than aggressively increasing TV spending, the company should focus on:

Campaign optimization
Better audience targeting
Strategic scheduling
Regional advertising effectiveness
Expected Business Impact
Improved brand positioning
Better campaign reach
Enhanced multi-channel marketing effectiveness

##4. Reevaluate Social Media Marketing Strategy
SocialMedia_Spend

Social Media marketing showed relatively lower direct ROAS compared to Radio and Search Ads.

Possible Reasons
Weak conversion-focused campaigns
High competition on digital platforms
Spending focused more on engagement than conversions
Long-term branding effects not fully captured in the regression model
Strategic Recommendation

Instead of eliminating Social Media marketing entirely, the company should:

Optimize campaign objectives
Improve audience segmentation
Focus on conversion-oriented advertisements
Conduct A/B testing for campaigns
Monitor engagement-to-conversion ratios
Expected Business Impact
More efficient social media campaigns
Improved conversion rates
Reduced unnecessary ad spending

##5. Reduce or Restructure Influencer Marketing Spend
Influencer_Spend

Influencer marketing generated the lowest modeled ROAS in the analysis.

Key Concerns
Weak direct contribution to short-term sales
High campaign costs relative to returns
Difficulty measuring exact conversion impact
Strategic Recommendation

The company should:

Reduce ineffective influencer collaborations
Prioritize niche influencers with stronger engagement
Focus on measurable campaign KPIs
Use performance-based influencer partnerships
Expected Business Impact
Reduced marketing waste
Better allocation of advertising budget
Improved ROI tracking

##6. Implement Data-Driven Budget Allocation

The company should move away from intuition-based marketing decisions and adopt data-driven allocation strategies.

Recommended Approach

Allocate larger budgets toward channels with:

Higher ROAS
Stronger regression coefficients
Better conversion efficiency
Consistent sales contribution
Benefits
Improved profitability
Better marketing accountability
Higher return on marketing investment

##7. Continuously Monitor Campaign Performance

Marketing performance changes over time due to:

Consumer behavior shifts
Seasonal demand
Competitor activities
Market trends
Strategic Recommendation

The company should establish a continuous monitoring framework including:

Monthly ROI analysis
Campaign performance dashboards
Quarterly budget optimization reviews
Predictive analytics updates
Expected Business Impact
Faster response to market changes
Better budget control
Sustainable marketing growth 

---


# Project Structure

```bash
Market-Basket-Analysis/
│
├── Market_Basket_Analysis.ipynb
├── README.md
├── requirements.txt
├── dataset_source.md
├── outputs/
└── images/
```

---

# How to Run the Project

## Step 1: Clone Repository

```bash
git clone [<repository-link>](https://github.com/TaranpreetKaur06/Market-Basket-Analysis)
```

---

## Step 2: Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## Step 3: Open Jupyter Notebook or Google Colab

Open:

```bash
Market_Basket_Analysis.ipynb
```

---

## Step 4: Run All Cells

Execute all notebook cells sequentially.

---

# Google Colab Notebook

You can also view and run the project directly in Google Colab using the notebook link included in this repository.

---

# Conclusion

This project successfully used Multiple Linear Regression to analyze the impact of marketing spend on sales revenue.

The analysis identified:

* High-performing marketing channels
* Less efficient spending areas
* Opportunities for budget optimization

The results suggest that reallocating budget toward high-ROAS channels such as Radio and Search Ads can improve overall marketing efficiency and maximize revenue generation.

This project demonstrates how regression analysis can support strategic business decision-making and data-driven marketing optimization.
