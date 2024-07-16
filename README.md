# Retailing-Data-Mining-Project
This project scrutinized a dataset from a large international store. Through analysis, the aim is to provide actionable recommendations to the store owner, facilitating profit maximization by leveraging Data Mining techniques to devise effective business strategies. The project encompasses several key stages: data preparation, preliminary analysis, clustering, word frequency analysis, association rule mining, and sales forecasting using Prophet.

1. Data Preparation:
The first step involved collecting and cleaning the sales data to ensure its quality and reliability. This process included handling missing values, removing duplicates, and transforming data into a suitable format for analysis. The cleaned dataset formed the foundation for all subsequent analyses.

2. Preliminary Analysis:
Extracting valuable information from substantial datasets is of paramount importance. This procedure, referred to as data mining, entailed the extraction and comprehension of pertinent data. Key statistics were calculated, such as:

  + Number of transactions and values each month, day, and hour in a day.
  + Identification of top products purchased by customers.
  + Analysis of sales contributions by country.
  + Customer classification based on Recency, Frequency, and Monetary (RFM) values.

3. Clustering:
The processed data was collected based on the modified StockCode, serving as the identification key. From the original dataset, RFM scores were extracted. Using these scores, customers were classified into four distinct categories:

  + New customers
  + Customers at risk
  + Lost customers
  + Loyal customers
   
5. Word Frequency Analysis:
This research employed sentiment analysis to tally high-frequency words within customer reviews and feedback. By identifying common terms and phrases, we gained insights into customer preferences and sentiments. This information guided recommendations regarding product types and characteristics to suggest. This strategy enabled merchants to understand purchasing patterns and behaviors, allowing them to design more successful and personalized marketing strategies.

6. Association Rule Mining:
Market basket analysis was performed using the Association Rules (AR) approach, best represented by the Apriori Technique. This method examined transactional data to reveal strong trends by identifying relationships that occurred more frequently than anticipated. It gauged the frequency of co-occurring items, providing insights into product combinations that customers often purchased together.

7. Sales Forecasting with Prophet:
Prophet, a forecasting tool developed by Facebook, was used to predict future sales trends. This involved modeling the time series data to account for various factors such as seasonality, holidays, and other important events. The resulting forecasts provided actionable insights for inventory management, sales planning, and strategic decision-making.
