# OilyGiant_Profit_Prediction_ML_Project
You work for the OilyGiant mining company. Your task is to find the best place for a new well.

## Project Intro:

In this project, we are working for a company named OilyGiant. We are tasked with finding the best place for a new well. To do this we collect oil well parameters in the selected regions. Next, we will build a model for predicting the volume of reserves in the new wells. After, we will pick the oil wells with the highest estimated values. Last, we will pick the region with the highest total profit for the selected wells. We will analyze profit and risks using the Bootstrapping technique.

## Data Description
Geological exploration data for the three regions are stored in files:

- `geo_data_0.csv`
- `geo_data_1.csv`
- `geo_data_2.csv`
- `id` — unique oil well identifier
- `f0, f1, f2` — three features of points (their specific meaning is unimportant, but the features themselves are significant)
- `product` — volume of reserves in the oil well (thousand barrels).


 ## Conclusion

- Highest Average Profit: Region 1 has the highest average profit of approximately $4,302,083.52.

- Narrower Confidence Interval: The 95% confidence interval for Region 1 ranges from $430,525.20 to $8,473,134.67.

- Lowest Risk of Losses: Region 1 has the lowest risk of losses at just 1.60%.

- Positive Lower Bound: Unlike Region 0 and Region 2, which have negative values in their confidence intervals, Region 1's lower bound is positive, further supporting the decision to focus on this region.

Given the analysis of average profits, confidence intervals, and risk of losses, Region 1 is the most promising choice for the development of oil wells. It provides the best combination of potential profit and low risk, making it a strategic option for investment in the oil exploration and extraction process.
