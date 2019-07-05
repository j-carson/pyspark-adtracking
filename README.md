# pyspark-adtracking

## About the dataset

The dataset is from TalkingData, a Chinese data service platform, for the 
[Ad Tracking Fraud Detection contest](https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/overview)

The goal is to identify which ad clicks for mobile apps are legitimate clicks based on the propensity of ad clicks to 
result in an actual app download. The remaining clicks are suspected fraud. 

The dataset is highly imbalanced, consisting of almost 190 million rows, with approximately a half-million actual app downloads. 

## Techniques used

- Feature engineering
- Subsampling
- Class rebalancing
- Pyspark
  - SQL Library
  - ML Classification Library
