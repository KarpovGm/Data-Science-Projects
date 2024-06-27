# Customer Segmentation for an Online Gift Store

## Table of Contents  
[1. Project Description](#Project-Description)  
[2. Business Challenge](#Business-Challenge)  
[3. Project Objectives](#Project-Objectives)  
[4. Data Description](#Data-Description)  
[5. Solution Steps](#Solution-Steps)
[6. Tools Used](#Tools-Used) 
[7. Results](#Results) 
[8. Conclusions](#Conclusions) 

### Project Description    

Marketing is an integral part of any business. To increase company profits, it is crucial to understand the customer, their desires, and preferences. Machine learning helps analyze vast amounts of data about platform visitors, learn customer behavior patterns, and determine customer segments. In this project, we conducted customer segmentation for an online gift shop based on their purchasing behavior.

:arrow_up:[back to top](#Table-of-Contents)


### Business Challenge  

**Business Task**
The project's goal was to segment existing customers and determine strategies for interacting with them to increase the effectiveness of marketing campaigns.

**Technical Task**
Machine learning methods were used to address the business challenge. The main stages of work included data preprocessing, analysis of main characteristics, creation of new features, customer segmentation, and visualization of results.

### Project Objectives

1. Conduct data preprocessing and exploratory data analysis.
2. Build clustering models and determine the optimal number of clusters.
3. Interpret the resulting clusters and define strategies for interacting with each customer group.
  
:arrow_up:[back to top](#Table-of-Contents)


### Data Description

The dataset contains all transactions from 01/12/2010 to 09/12/2011 for a company engaged in online retail of gifts. The data includes the following features:

* **InvoiceNo** — invoice number (unique six-digit nominal number assigned to each transaction; 'C' at the beginning of the code indicates a canceled transaction);
* **StockCode** — product code (unique five-digit integer assigned to each individual product);
* **Description** — product name;
* **Quantity** — the quantity of each product per transaction;
* **InvoiceDate** — invoice/transaction date and time;
* **UnitPrice** — price per unit in pounds sterling;
* **CustomerID** — customer identifier (unique five-digit number uniquely assigned to each customer);
* **Country** — the name of the country where the customer resides.

[Download Data](https://lms-cdn.skillfactory.ru/assets/courseware/v1/468638e49cb9e7d4b4dfdc296c1c778e/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/pj6_data.zip)

:arrow_up:[back to top](#Table-of-Contents)


### Solution Steps  

1. Familiarization with the data structure
   1.1. Data transformation, cleaning, and analysis
   1.2. Feature engineering
   1.3. Exploratory data analysis of transactions
   1.4. Building an RFM table and identifying RFM outliers
2. Modeling and model evaluation
   2.1. Clustering based on RFM characteristics
   2.2. Cluster interpretation

:arrow_up:[back to top](#Table-of-Contents)

### Tools Used

1. Programming language Python
2. Data manipulation libraries: 
* Pandas
* Numpy
3. Visualization libraries:
* matplotlib
* Seaborn
* Plotly
4. Machine learning libraries:
* Scikit-Learn

### Results
Based on the RFM analysis, I reduced the dimensionality of the data for more vivid visualization and ease of segmentation, found the optimal number of clusters using the silhouette method, and used the KMeans algorithm to segment customers based on their loyalty. To make the segments more distinct, I created a cluster profile using a Radar Chart, clearly highlighting the following segments: **loyal**, **promising**, **drifting**, **newcomers**, **at risk**, and **sleeping/gone**.

:arrow_up:[back to top](#Table-of-Contents)


### Conclusions 

I believe the project was well executed; the segmentation was quite successful, with clusters that are interpretable and distinguishable from each other. Certainly, the work can and should be continued to extract the maximum from the data and provide the business with even more information for implementing a marketing campaign. For instance, future steps could include:

* Segmenting wholesalers separately. Here, the idea of the RFM method is expanded by adding information about the average number of items purchased per order to the dataset. Thus, the RFM acronym becomes RFMQ, where Q stands for the average quantity of products per order.
* Performing a cluster analysis of products based on their description and forming categories of purchases.
* Calculating the purchase frequency of each product category for each customer. This information could be the basis for building a clustering model and segmenting customers based on their interests.
* Finally, using information about the seasonality of purchases and adding data on the frequency of customer purchases in each month. This could determine which customers are regulars, whose purchases do not depend on the season, and which only buy products in anticipation of holidays. This information allows for experimentation with the marketing campaign and enhancing customer loyalty.

Unfortunately, at this time, I do not have the resources to implement these ideas, but as soon as they become available, I look forward to returning to the project.

:arrow_up:[back to top](#Table-of-Contents)


