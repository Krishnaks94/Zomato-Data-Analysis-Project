# Zomato Data Analysis Project

## Description
This project analyzes data from Zomato to understand customer preferences and restaurant performance. The goal is to uncover patterns and insights that can help make better business decisions. The analysis involves cleaning the data, exploring it, and creating visualizations to answer important questions about restaurants and customer behavior.

## Objectives
In this project, we aim to:
- Find out which types of restaurants are the most popular.
- See how many votes different types of restaurants get from customers.
- Understand the ratings that most restaurants receive.
- Look at how much couples usually spend on orders.
- Check if offering online ordering affects customer ratings.

## Dataset Information
The dataset contains details about restaurants on Zomato, including:
- **Restaurant Type**: For example, "Casual Dining" or "Quick Bites."
- **Customer Votes**: The number of votes each restaurant received.
- **Ratings**: The average rating given by customers.
- **Cost for Two**: An estimate of how much it costs for two people to eat there.
- **Online Order Availability**: Whether the restaurant offers online ordering.

## Requirements
You need the following Python libraries to run this project:
- **pandas**: For working with the data.
- **numpy**: For mathematical calculations.
- **matplotlib**: For creating graphs.
- **seaborn**: For advanced and beautiful visualizations.

## Methodology
1. **Importing Libraries**: 
   - Loaded all the necessary libraries like `pandas` and `seaborn`.

2. **Loading Data**: 
   - Read the dataset into a table using `pandas`.

3. **Cleaning the Data**:
   - Fixed problems in the dataset, such as changing ratings into numbers so they can be analyzed.

4. **Exploring the Data**:
   - Answered key questions using simple calculations and graphs.
     - Example questions:
       - What types of restaurants are most popular?
       - How many votes do different restaurant types get?
       - What ratings are most common?

5. **Visualizing the Data**:
   - Used graphs to make the analysis easy to understand. Examples include:
     - Bar graphs for restaurant types.
     - Line graphs for votes.
     - Histograms for ratings.

## Key Findings
1. **Popular Restaurant Types**:
   - Customers mostly prefer casual dining and quick bites.

2. **Votes**:
   - Fine dining restaurants get lots of votes even though there are fewer of them.

3. **Ratings**:
   - Most restaurants have ratings between 3.5 and 4.5.

4. **Spending Patterns**:
   - Couples usually spend a moderate amount, with clear trends in cost for two people.

5. **Online Orders**:
   - Restaurants that offer online ordering often have better customer ratings.
