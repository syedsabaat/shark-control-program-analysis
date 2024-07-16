# Shark Control Program Catch Analysis

## Executive Summary

This project's objective is to investigate patterns in shark catch counts according to species, location, month, and length found in data from the Shark Control Program. 

### Key Findings:
- **Tiger Shark** is the most caught species with a total of 207 catches.
- The median length of Tiger Shark is 2.37 meters.
- The highest number of sharks are caught in **February** and in the town of **Townsville**.

## Full Report

### Initial Data Analysis (IDA)

The data used in this analysis comes from the Agriculture & Fisheries Department of the State of Queensland. The dataset contains data from each day of 2016 and was collected as part of the Queensland Shark Control Program, a Government initiative to prevent shark bites.

#### Data Overview:
- Each row represents a shark caught and its respective data.
- Key variables include Species, Length, Month, and Area.

### Research Questions:

#### 1. What is the most caught shark species?
We analyzed which shark species was caught the most in 2016, producing an interactive bar plot representing the number of sharks caught for each species.

#### Findings:
- **Tiger Shark**: 207 catches
- **Bull Whaler**: 91 catches
- **Common Blacktip Whaler**: 39 catches

We also compared the median length of the top three most caught species.

#### 2. How do shark catch numbers vary by month and area?
We analyzed which month had the most sharks caught, producing an interactive bar plot sorting months by the number of sharks caught in descending order.

#### Findings:
- **February**: Highest number of shark catches (70)
- **Townsville**: Highest number of shark catches by area (112)

### Hypothesis Test: Correlation between Length of Sharks and Water Temperature
We performed a Pearson’s correlation test to see if there is a correlation between the length of sharks and the water temperature.

#### Conclusion:
The p-value is 0.03124, which is less than 0.05. Therefore, we reject the null hypothesis, indicating a correlation between the length of the sharks caught and the temperature of the water.

## References
- [Shark Control Program Catch Statistics](https://www.data.qld.gov.au/dataset/shark-control-program-shark-catch-statistics/resource/5c6be990-3938-4125-8cca-dac0cd734263)
- [Are we seeing more sharks than usual at this time of year?](https://www.abc.net.au/science/articles/2010/11/04/3056893.htm)
- [The Five Assumptions for Pearson Correlation](https://www.statology.org/pearson-correlation-assumptions/)

## Usage
Clone the repository and run the provided scripts to perform the analysis. Data visualization and hypothesis testing scripts are included to replicate the findings and explore further insights.

