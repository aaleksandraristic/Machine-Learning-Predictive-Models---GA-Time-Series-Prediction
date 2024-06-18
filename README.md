**Machine Learning Predictive Models - GA Time Series Prediction**


The goal of this project is to develop an accurate and reliable closing daily stock price prediction using historical stock data, to assist investors, traders, and
financial analysts make informed decisions about buying or selling stocks in a dynamic market.

Dataset
The dataset consisted of historical daily closing stock prices starting from August 20, 2004, to October 25, 2023, including a profile of 12 diverse technology companies.
These companies, drawn from the dynamic tech sector, showcase the evolution of their stock values over nearly two decades. The dataset serves as a valuable resource for
understanding market trends, assessing long-term performance, and conducting insightful analyses on the stock behavior of prominent tech entities. The data source,
retrieved from https://finance.yahoo.com/, ensures reliability and accessibility, laying the foundation for comprehensive examinations of stock market dynamics within the
specified time frame.

● Daily closing stock prices of 12 different tech companies, which are listed below:
● A period: 08/20/2004 to 10/25/2023
● Historical Data Source: https://finance.yahoo.com/

- AAPL - ADBE - AMZN - CRM
- CSCO - GOOGL - INTC - IBM
- MSFT - NFLX - NVDA - ORCL

**Methods**
**Clustering Model**
Clustering is the technique of dividing the population or data points into several groups such that data points in the same groups are more similar to other data points in
the same group and dissimilar to the data points in other groups. It is a collection of objects based on similarity and dissimilarity between them. 
K-means is a data clustering approach for unsupervised machine learning. It can separate unlabeled data into a predetermined number of disjoint groups of equal
variance – clusters – based on their similarities. It's a popular algorithm thanks to its ease of use and speed on large datasets.

![image](https://github.com/aaleksandraristic/Machine-Learning-Predictive-Models---GA-Time-Series-Prediction/assets/140200824/ce68ffef-1981-470d-ac8c-cdeb2a053e1c)
![image](https://github.com/aaleksandraristic/Machine-Learning-Predictive-Models---GA-Time-Series-Prediction/assets/140200824/fb06ef2a-8940-448f-9803-e4c22cae84a6)

**Arima Model**
ARIMA, short for "autoregressive integrated moving average," is a statistical and econometric model designed for the analysis of events occurring over time. This model
proves invaluable in comprehending historical data trends and forecasting future data points within a series. Particularly suited for metrics recorded at regular intervals,
ranging from fractions of a second to daily, weekly, or monthly periods, ARIMA leverages past values to predict future points in a given time series. Its versatility
extends to applications such as time series forecasting and the prediction of future stock prices, making it a widely employed tool in diverse fields reliant on temporal data
analysis.

**Shapelet Model**
The Shapelet machine learning model represents a specialized approach for time series classification. It operates in the way of identifying significant sub-patterns, known
as shapelets, within the time series data. These shapelets serve as markers, allowing for the comparison and classification of various time series based on their similarity to
these patterns. The model excels in capturing localized patterns within the time series data, making it particularly effective in situations where discriminative features are not
uniformly distributed across the entire sequence. This capability positions the Shapelet model as a valuable tool for accurate predictions and classification tasks in scenarios
characterized by uneven feature distribution.

 
[Final Project - Report CSC 667.pdf](https://github.com/aaleksandraristic/GA-s-Stock-Prediction-/files/13533755/Final.Project.-.Report.CSC.667.pdf)
