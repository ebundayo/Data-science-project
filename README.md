# Recommendation Engine


### Introduction
With increased popularity and growth in the grocery store, movies, and event-based online and offline services like Walmart, Netflix, Google, Spotify, Amazon, Meetup, it has become difficult for customers to find items, movies, books, events that match their interests. Hence, many online businesses rely on customer reviews and ratings.

Building a strong recommendation engine would be the natural answer to this problem. 

Recommendation Engine is a type of data filtering tool using machine learning algorithms to recommend the most relevant items to a particular user or customer. It operates on the principle of finding patterns in consumers’ behavior data, which can be collected implicitly and explicitly.

Explicit feedback is especially important in the entertainment and eCommerce industry where all customer engagements are impacted by these ratings. Netflix uses a recommendation engine to present viewers with movie and show suggestions. Amazon, on the other hand, uses a recommendation engine to present customers with product recommendations. While each uses one for slightly different purposes, both have the same goal: to drive sales, boost engagement and retention, and deliver more personalized customer experiences.

Today, we have passed this task in the hands, or minds, of algorithms. As a marketing tool, we could say that these machines are well-trained in the art of up-selling and cross-selling.

 ## Business Understanding
 - Retail is the process of selling consumer goods or services to customers through multiple channels of distribution to earn a profit.- This case has some business question using the data:
- What is percentage of sales by Product Name?
- Which Sub-Product Category boost sales for AHG?
- Who is the Top Customers and by what count of order?

## Data Understanding

Source Data: https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorksDW2012.bak (AdventureWorks sample database)

The dataset has 15 columns and 60398 rows.
Data Dictionary:

 ## Data preparation
 -  The project was implemented in python 3.7.3
 -  Packages: Pandas, Numpy, Pyodbc, Matplotlib, Seaborn, Sklearn, Scipy.Sparse, Implict, Random, Csr_matrix, Display_html,Cosine, Datetime, MinMaxScaler  and Features Engine.
    
 ## Approach
 
 - Data Pre-Processing: **Cleaning up data**, **Item lookup** and **Grouped count of products bought by Customers**.
 - Creation of Sparse Matrix: **Grouped purchase quantities** and **Rectangular arrangement of customers and items into rows and columns**
 - Building the recommendation system
 - Evaluating the recommendation system
 - Recommendation examples
  
  ## Conclusion
