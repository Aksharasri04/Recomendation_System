# Retail Recommendation System 👩‍💻🛒

## Objective 🚀

THE "RECOMMENDATION SYSTEM" AIMED TO CREATE A IDEA ABOUT WHICH ITEM IS TO RECOMMEND GLOBALLY, COUNTRY-WISE, AND MONTH-WISE, AND THE ITEM IS RECOMMENDED IS BASED ON ESTIMATED RATING AND USER RATING 

## Tasks Performed 📋

### 1. Data Preprocessing 📊
- Reads the retail dataset from an Excel file.
- Cleans the data by dropping missing values and filtering non-positive quantities.

### 2. Exploratory Data Analysis (EDA) 🕵️‍♀️
- Provides insights into available countries and items.
- Displays transaction counts by country.
- Identifies and showcases the most popular items globally and country-wise.

### 3. Association Rule Mining ⛏️
- Utilizes the Apriori algorithm for monthly transaction data.
- Discovers frequent itemsets and association rules based on support and lift thresholds.

### 4. Visualization 📈
- Creates a visual representation of the most popular items globally using a histogram plot.
- Displays the count of repeated products each month.

### 5. Collaborative Filtering ⚙️
- Implements the Surprise library's SVD algorithm for building a recommendation model.
- Trains the model using the retail dataset.
- Generates predictions for user-item interactions.

### 6. Top-N Recommendations 🎯
- Generates top-N recommendations for each user through collaborative filtering.
- Creates a dictionary containing recommended items for each user.
- Displays the most recommended items overall, considering the number of recommendations.

## Need for the Proposed System 🌐

### Global Need 🌎
- **Personalization:** Users expect personalized experiences, and recommendation systems analyze preferences to enhance satisfaction.
- **Information Overload:** Alleviates information overload by suggesting relevant items, saving time and effort.
- **Business Competitiveness:** Enhances customer engagement and boosts sales.

### Monthly Need 📅
- **Seasonal Trends:** Adapts to user preferences influenced by holidays and events.
- **Content Updates:** Incorporates the latest content for up-to-date recommendations.

### Country-wise Need 🌍
- **Cultural Differences:** Considers unique cultural preferences for relevant recommendations.
- **Localized Content:** Recommends country-specific items or content.
- **Market Dynamics:** Adapts to economic conditions, industry trends, and user behavior in each market.

## Methodology 🛠️

### 1. Data Preprocessing 🧹
- Drops missing values and filters out non-positive quantities.

### 2. Exploratory Data Analysis (EDA) 📊
- Analyzes trends, identifies popular items globally and by country.

### 3. Association Rule Mining ⛏️
- Uses Apriori algorithm to identify frequent itemsets and association rules.

### 4. Visualization 📈
- Visualizes popular items globally using a histogram plot.

### 5. Collaborative Filtering ⚙️
- Employs Surprise library's SVD algorithm to build a recommendation model.

### 6. Top-N Recommendations 🎯
- Generates top-N recommendations for each user based on the collaborative filtering model.

## Methodology Details 📘

### 1. Data Preprocessing 🧹
The first step is to preprocess the data by dropping missing values and filtering out non-positive quantities. This ensures that the data is clean and consistent, which is necessary for the analysis to produce accurate results.

### 2. Exploratory Data Analysis (EDA) 📊
The next step is to perform exploratory data analysis (EDA) on the dataset. This involves analyzing the data to identify trends and patterns. For example, the code can be used to identify the most popular items globally and by country. This information can be used to create targeted recommendations.

### 3. Association Rule Mining ⛏️
Association rule mining is a technique that can be used to identify items that are frequently purchased together. This information can be used to generate recommendations for users who have purchased similar items in the past. For example, if a user has purchased a book about cooking, the code can recommend other cooking-related books or kitchen utensils.

### 4. Visualization 📈
The code can be used to visualize the data to make it easier to understand. For example, the most popular items globally can be visualized using a histogram plot. This makes it easy to see which items are most popular and how they compare to each other.

### 5. Collaborative Filtering ⚙️
Collaborative filtering is a technique that can be used to recommend items to users based on their past ratings. This is a personalized approach that can help users discover new items that they are likely to enjoy. The code can be used to train a collaborative filtering model using the retail dataset. This model can then be used to generate recommendations for users.

### 6. Top-N Recommendations 🎯
The final step is to generate top-N recommendations for each user. This involves sorting the recommended items for each user based on estimated ratings. The most recommended items overall, considering the number of recommendations, can also be displayed.

This proposed methodology is a scalable, flexible, and reliable approach that can be used to develop a recommendation system for a retail dataset. It can be used to generate personalized recommendations for users, enhance the user experience, increase user engagement, and facilitate item discovery.

## Output Screenshots 📸

### HOMEPAGE

<img align="center" alt="coding" width="700" src="https://github.com/Aksharasri04/Recomendation_System/blob/main/SS/1.jpg">

### COUNTRIES AND ITEMS AVAILABLE

<img align="center" alt="coding" width="700" src="https://github.com/Aksharasri04/Recomendation_System/blob/main/SS/2.jpg">

### MOST POPULAR ITEMS GLOBALLY AND COUNTRY WISE

<img align="center" alt="coding" width="700" src="https://github.com/Aksharasri04/Recomendation_System/blob/main/SS/3.jpg">

### MOST POPULAR ITEMS GLOBALLY USING SEABORN LIBRARY

<img align="center" alt="coding" width="700" src="https://github.com/Aksharasri04/Recomendation_System/blob/main/SS/4.jpg">

