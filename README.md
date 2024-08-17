# Target-Retail-Customer-Purchase-Analysis-using-SQL

# 🚀 Welcome to the Target Order Analysis Project! 🎉

As a data scientist at Target, you've been entrusted with a fascinating project: analyzing 100,000 orders placed between 2016 and 2018 at Target locations in Brazil. 🌎🇧🇷

📚 The dataset consists of 8 CSV files:

* **customers.csv** 🧑‍🤝‍🧑
* **geolocation.csv** 🗺️
* **order_items.csv** 🛍️
* **payments.csv** 💳
* **reviews.csv** 📝
* **orders.csv** 📦
* **products.csv** 📝
* **sellers.csv** 👩‍💼

### 🔍 What Are We Looking For?

We'll begin by importing the dataset and conducting an exploratory analysis. This involves examining the structure, characteristics, data types, and the time period covered by the data. Additionally, we'll explore the geographic distribution of customers—specifically the cities and states from which orders were placed during the period in question. 🕵️‍♀️

### 🔍 Deep Dive Analysis:

* **Is e-commerce in Brazil on the rise?** 📈 What trends can we observe? 🤔 Is there any seasonality with noticeable peaks in certain months? ❄️☀️
* **When do Brazilian customers prefer to shop?** 🕒 Are they more active at dawn, morning, afternoon, or night? 🌅🌇🌄🌃

#### Evolution of E-commerce Orders in Brazil:

* **Monthly Orders by State:** Track the number of orders each month, categorized by state. 📊
* **Customer Distribution:** Visualize the spread of customers across Brazilian states. 🗺️👥
* **Economic Impact:** Assess the financial flow within e-commerce by examining order prices, freight charges, and other costs.
* **Cost Increase Analysis:** Calculate the percentage increase in order costs from 2017 to 2018 (focusing on January to August). Utilize the “payment_value” field in the payments table for this analysis. 💰
* **Freight and Pricing Analysis by State:** Determine the mean and sum of order prices and freight charges by state. 💵🚛
* **Sales, Freight, and Delivery Time Analysis:** 📊🚚
  * **Days Between Purchase and Delivery:** Calculate the duration between the purchase date, delivery date, and estimated delivery date. 📅
  * **Delivery Efficiency:** Find out the actual delivery time versus the estimated time (time_to_delivery & diff_estimated_delivery). ⏳
  * **State-wise Freight and Delivery Analysis:** Group data by state, calculating the mean for freight_value, time_to_delivery, and diff_estimated_delivery. 📊

#### Sorting the Data:

* **Top 5 States by Freight Value:** Identify the top 5 states with the highest and lowest average freight values, sorted in descending and ascending order, respectively. 📉📈
* **Top 5 States by Delivery Time:** Highlight the top 5 states with the longest and shortest average delivery times. 🚛⏰
* **Top 5 States by Delivery Speed:** Determine the top 5 states where delivery is either faster or slower than the estimated date. 🚚⚡

#### Payment Type Analysis: 💳

* **Monthly Payment Method Trends:** Track the number of orders each month, broken down by payment type. 📊
* **Installment-Based Orders:** Count the orders based on the number of payment installments selected. 🔢

### 📊 Let’s Dive into the Data!

With all this in mind, let's dig into the dataset and uncover some valuable insights. 💻 Happy analyzing! 🤓

Please refer to the report for a detailed analysis.📊✨
