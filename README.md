# FUTURE_DS_02
# customer support ticket

# Project Overview

 This project explores and visualizes a dataset of customer support tickets to extract insights into customer behavior, service efficiency, and product issues. It uses Python for data processing and visualization.
The goal is to analyse trends ,relationships and make data driven recommendation to improve performance.
The dataset is processed in  Jupyter Notebook, and a Power BI dashboard for reporting.

# Data source 

The customer support ticket data is a secondary data which contains information on customers issues ,it is recorded in an excel file.

# Tools 

Python: Pandas, Seaborn, Matplotlib, Plotly for  data manipulation and  visualization
Power BI: Interactive dashboards for  data reporting .
Jupyter Notebook: Data preparation and exploratory analysis.

# Data Cleaning and preparation

In the first phase ,the data is loaded into the jupiter notebook for the data processing .
steps:
   - Loading the dataset
   - Reset index
   - Dropping missing values
   - Performing sentimental analysis.
   - Feature Engineering

# Exploratory Data Analysis

The EDA involves exploring the social media data to answer key questions.
    - Which ticket type is most occuring?
    - which product has the highest issues reported?
    - what is the distribution interms of ticket priority?
    -what is the trend across the year in terms of ticket count?
    
# Data Analysis.
Data analysing using various visualization  plots are generated using libraries like Matplotlib, Seaborn.
Among them is a line graph to show trend and identify patterns over time in the customer tickets .
A bargraph to compare the distribution sentiments and customers ratings.
code:
```python
import seaborn as sns #For data visualization
import matplotlib.pyplot as plt #For data visualization

#Compare the sentiments with the Customer Satisfaction Rating
sns.barplot(x="Customer Satisfaction Rating",y="compound",data=data)
plt.title("Comparing Sentiment with Ratings")
plt.show();

```

# Findings
-Technical issues and Refund requests are the most frequent types of tickets.
-A large portion of tickets are marked as low or medium priority,few tickets are marked as critical, indicating most customer concerns are not emergencies.
-Products like GoPro Hero, LG Smart TV,  generate more tickets.
-A significant number of tickets are closed, but some remain in pending customer response.
-Ticket volume fluctuates by month, possibly peaking during promotional  holidays.

# Recommedations
-Improve technical and billing documentation for common issues by focus on accuracy, and completeness, ensuring all relevant details are recorded 
and easily accessible
-Consider using chatbots for low-priority queries,to automate customer support, and offer instant information retrieval
- Monitor and optimize slow resolution cases.
-Boost follow-up mechanisms for tickets that are pending customer response.
