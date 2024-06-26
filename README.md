# Machine Learning Predictive Models - GA Time Series Prediction


Developing an accurate and reliable **financial prediction model** for the next 5 years using historical data, to assist investors, traders, and
financial analysts make informed decisions about buying or selling stocks in a dynamic market.

# Dataset

- 20 years old data: historical daily closing stock prices
- period: 08/20/2004 to 10/25/2023
- 12 different tech companies:

  - AAPL - ADBE - AMZN - CRM
  - CSCO - GOOGL - INTC - IBM
  - MSFT - NFLX - NVDA - ORCL

- resource: https://finance.yahoo.com/

# Key Contributions:
- Data Collection, Cleaning & Preprocessing 
- Data Visualization 
- Data Splitting 
- Model Selection 
- ARIMA Model Development, Fine-Tuning & Evaluation 
- Comparison to the Shapelet model that a colleague from my team did 
- Project Management 
- Fixing Bugs 
- Project Defense

# Methods

**1. Clustering Model**
Clustering is the technique of dividing the population or data points into several groups such that data points in the same groups are more similar to other data points in
the same group and dissimilar to the data points in other groups. It is a collection of objects based on similarity and dissimilarity between them. 
K-means is a data clustering approach for unsupervised machine learning. It can separate unlabeled data into a predetermined number of disjoint groups of equal
variance – clusters – based on their similarities. It's a popular algorithm thanks to its ease of use and speed on large datasets.

![image](https://github.com/aaleksandraristic/Machine-Learning-Predictive-Models---GA-Time-Series-Prediction/assets/140200824/ce68ffef-1981-470d-ac8c-cdeb2a053e1c)
![image](https://github.com/aaleksandraristic/Machine-Learning-Predictive-Models---GA-Time-Series-Prediction/assets/140200824/fb06ef2a-8940-448f-9803-e4c22cae84a6)

**2. Arima Model**
ARIMA, short for "autoregressive integrated moving average," is a statistical and econometric model designed for the analysis of events occurring over time. This model
proves invaluable in comprehending historical data trends and forecasting future data points within a series. Particularly suited for metrics recorded at regular intervals,
ranging from fractions of a second to daily, weekly, or monthly periods, ARIMA leverages past values to predict future points in a given time series. Its versatility
extends to applications such as time series forecasting and the prediction of future stock prices, making it a widely employed tool in diverse fields reliant on temporal data
analysis.

![image](https://github.com/aaleksandraristic/Machine-Learning-Predictive-Models---GA-Time-Series-Prediction/assets/140200824/93aaf874-d3fb-4564-b967-f89b9480eb86)


**3. Shapelet Model**
The Shapelet machine learning model represents a specialized approach for time series classification. It operates in the way of identifying significant sub-patterns, known
as shapelets, within the time series data. These shapelets serve as markers, allowing for the comparison and classification of various time series based on their similarity to
these patterns. The model excels in capturing localized patterns within the time series data, making it particularly effective in situations where discriminative features are not
uniformly distributed across the entire sequence. This capability positions the Shapelet model as a valuable tool for accurate predictions and classification tasks in scenarios
characterized by uneven feature distribution.

![image](https://github.com/aaleksandraristic/Machine-Learning-Predictive-Models---GA-Time-Series-Prediction/assets/140200824/a3215cba-ca52-4a62-8d70-6bbec2640c05)


 
[Final Project - Report CSC 667.pdf](https://github.com/aaleksandraristic/GA-s-Stock-Prediction-/files/13533755/Final.Project.-.Report.CSC.667.pdf)
