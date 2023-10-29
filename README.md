# Restaurant-Recommendation

## Overview:

This Repo deals with a comprehensive restaurant recommendation system that encompasses data merging, cleaning, exploratory data analysis (EDA), and various recommendation techniques. The goal of this project is to provide personalized restaurant recommendations to users based on their preferences and historical data.

Moreover, a WebPage was Developed with help of Flask to Get the Recommendation Similar to a Restaurant as per User's input. The WebPage then provides the response with the Recommended Restaturants with their calculated Ratings based on different Techniques.

Further, Docker Image was created using which the Website could be lauched & used.

## Techincal Details :

**1. Data Integration:**

Initially, Data Source is from three separate CSV files. They were integrated into a single dataframe, making it a centralized source for further analysis.

**2. Data Cleaning:**

We applied data cleaning techniques to ensure data quality:
Removed duplicate records to eliminate redundancy.
Handled missing values effectively, ensuring data completeness.

**3. Exploratory Data Analysis (EDA):**

EDA was conducted to gain insights into the dataset and visualize patterns.
Utilized various visualization techniques to understand data distributions and relationships.
Explored statistical properties and anomalies within the data.

## Recommendation Techniques:

**1. Weighted Average Recommendation:**

This recommendation method calculates a weighted average rating for each restaurant based on user reviews and ratings. Restaurants with higher weighted averages are recommended as they tend to be more popular and well-rated.

**2. Correlation-Based Rating Recommendation:**

This technique leverages customer ratings and identifies correlations between user preferences. It recommends restaurants based on the preferences of users who have given ratings similar to the user's preferences.

**3. K-Nearest Neighbors (KNN) Rating Recommendation:**

The KNN algorithm suggests restaurants by considering the preferences of users who are most similar to the current user. This method relies on user-user similarity to make recommendations.

**4. Content-Based Recommendation:**

Content-based recommendations are made based on the type of food that a restaurant offers. Text data related to restaurant descriptions is processed using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization, a text classification method, to understand the type of cuisine a restaurant provides. Users are then recommended restaurants that match their preferred cuisine.





With Help of Above Techniques, ".pkl" Files were developed and the same was used to provide Results for the inputs from the webpage by the user.


Run the below command to launch the App
```
docker-compose.yml
```

Please use the Datasets from the below Sheet to fetch the results:

[Restaurants List](https://docs.google.com/spreadsheets/d/113wqiLJCoTJlzEXNzgRfqT1D0_ixAZ2OINTuMR35UJM/edit?usp=sharing)

Demo Video :

https://github.com/adithyang64/Restaurant-Recommendation/assets/67658457/e2455920-803f-4c10-8166-1af76b60d93d

