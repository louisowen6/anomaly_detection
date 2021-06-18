# Time Series Anomaly Detection

This is the code implmentation of the published Medium Article: [Time Series Anomaly Detection: Simple Yet Powerful Approaches](https://louisowen6.medium.com/time-series-anomaly-detection-simple-yet-powerful-approaches-4449ffe1ca12). 

In this article, you will learn several simple yet powerful approaches to detect anomaly in time-series data that is not usually discussed in many articles. You will also learn how to generate the anomaly event label from scratch, ways to optimize your anomaly detection performance, and also ideas to validate the robustness of the system performance.

The data used in this experiment is a [generated dummy data](https://github.com/louisowen6/anomaly_detection/blob/main/dummy_topup_data.csv) about historical credits top-up at the e-commerce company. Each row represents the aggregation value within a 30-minutes interval. 


## Requirements

```
pandas, numpy, matplotlib, seaborn, tqdm, scikit-learn==0.23.2
```
