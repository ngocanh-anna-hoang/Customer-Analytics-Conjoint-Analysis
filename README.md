# Customer Analytics: Conjoint Analysis

## Project Overview

This project applies **conjoint analysis** to understand customer preferences and purchasing behaviour in the roofing shingles market. Using Excel-based regression analysis and a logit model, the project examines how product attributes influence customer choices, identifies differences between customer segments, and estimates purchase probabilities for different product bundles.

The analysis was conducted for a hypothetical business case involving **Homer & Co.**, with the objective of identifying product configurations that better align with customer preferences and support data-driven marketing and product development decisions.

## Business Problem

Understanding which product features matter most to customers helps businesses develop competitive offerings and allocate resources effectively.

This project investigates three key questions:

- Which roofing shingle attributes have the greatest influence on customer preferences?
- How do preferences differ across customer segments?
- Which product bundles have the highest estimated purchase probabilities compared with competitors?

## Dataset

The Excel workbook contains data and analysis for 20 respondents evaluating nine roofing shingle bundles.

Four product attributes were examined:

| Attribute | Levels examined |
|---|---|
| Life expectancy | Low, medium and high resistance |
| Speed of installation | 1 week, 1.2 weeks and 1.5 weeks |
| Shingle aesthetics | No imperfections and minimal imperfections |
| Price | Different price levels across the bundles |

The workbook includes bundle attribute coding, respondent-level regression outputs, attribute importance calculations, customer segmentation and purchase probability estimates.

## Methodology

### 1. Product Attribute Coding
Product attributes were converted into dummy variables to represent different attribute levels in the regression analysis.

### 2. Individual-Level Regression Analysis
Regression models were developed for individual respondents to estimate the utility associated with product attributes and levels.

### 3. Attribute Importance Analysis
The relative importance of each attribute was calculated using its utility range. These values were aggregated to understand the factors that influence customer preferences overall and within each segment.

### 4. Customer Segmentation
Respondents were grouped into three segments based on their preference patterns. Segment-level attribute importance and purchase probabilities were compared to identify differences in customer priorities.

### 5. Logit Model and Purchase Probability
A logit model was used to estimate purchase probabilities for the nine product bundles compared with competitors. Predicted choices were also compared with respondents' stated choices to evaluate model accuracy.

## Key Findings

### Overall Attribute Importance

The average relative importance of each attribute was:

| Attribute | Importance |
|---|---:|
| Speed of installation | 37.67% |
| Life expectancy | 35.91% |
| Price | 17.48% |
| Shingle aesthetics | 8.94% |

**Key insight:** Speed of installation and life expectancy were the two most influential attributes, accounting for approximately 73.84% of total attribute importance. This suggests that functional product benefits were more influential than aesthetics in this sample.

### Customer Segment Differences

Three customer segments were identified, with the following average attribute importance patterns:

- **Segment 1 (9 respondents):** Speed of installation was the leading attribute at 50.24%.
- **Segment 2 (8 respondents):** Life expectancy was the dominant attribute at 49.34%.
- **Segment 3 (3 respondents):** Life expectancy was the leading attribute at 33.30%, followed by speed of installation at 30.91% and price at 22.14%.

**Key insight:** Customer preferences were not uniform. Product positioning could be tailored to different segments, emphasising installation speed for Segment 1 and durability for Segments 2 and 3.

### Purchase Probability

The workbook's logit model estimated the following average purchase probabilities for the leading bundles:

| Bundle | Estimated purchase probability |
|---|---:|
| Bundle 1 | 89.13% |
| Bundle 7 | 53.00% |
| Bundle 2 | 50.41% |

Bundle 1 had the highest estimated purchase probability. It combined low resistance, a one-week installation time, no shingle imperfections and a price of 10 in the dataset's stated price units.

These probabilities are model-based estimates and should not be interpreted as actual market shares or guaranteed sales outcomes.

### Model Performance

The logit model correctly predicted the stated choices of **17 out of 20 respondents**, corresponding to an accuracy of **85%**.

This indicates that the model captured the stated choices of most respondents in the sample, although further validation with a larger dataset would be valuable.

## Business Recommendations

Based on the analysis, the following actions could be considered:

1. **Prioritise functional benefits:** Emphasise installation speed and life expectancy in product development and marketing.
2. **Use segment-specific messaging:** Highlight convenience and installation efficiency for customers who prioritise speed, and durability for customers who prioritise life expectancy.
3. **Evaluate bundle configurations:** Investigate why Bundle 1 received the highest estimated purchase probability and use it as a starting point for further product testing.
4. **Conduct further research:** Collect additional customer responses and validate the model to assess whether the observed preferences generalise to a broader market.

## Tools and Skills

- Microsoft Excel
- Conjoint analysis
- Dummy variable coding
- Regression analysis
- Utility estimation
- Customer segmentation
- Logit modelling
- Purchase probability estimation
- Business insight generation

## Files

- `Customer Analytics - Conjoint analysis.xlsx` — Excel workbook containing the dataset, bundle coding, respondent-level regression outputs, attribute importance calculations, customer segments and purchase probability results.

## Limitations

- The analysis is based on a sample of 20 respondents, which limits the generalisability of the findings.
- The identified customer segments are small, particularly Segment 3, which contains only three respondents.
- Estimated purchase probabilities depend on the model and the assumptions used in the analysis.
- Stated preferences may differ from actual purchasing behaviour.

## Conclusion

This project demonstrates how conjoint analysis can translate customer preference data into actionable business insights. By identifying important product attributes, comparing customer segments and estimating purchase probabilities, businesses can make more informed decisions about product configuration, positioning and marketing strategy.

