# Customer Segmentation Project

## Project Overview
This project focuses on customer segmentation using K-Means clustering. By analyzing a simulated dataset of customer demographics and behaviors, we identify distinct customer groups to help businesses create targeted marketing strategies and improve customer satisfaction.

## Objectives
- Perform data preprocessing, including scaling and encoding.
- Identify optimal clusters using the Elbow Method and Silhouette Scores.
- Interpret the characteristics of each cluster using descriptive statistics and visualizations.
- Provide actionable business recommendations based on cluster insights.

## Dataset
The dataset used in this project was sourced from Kaggle. You can find it [here](https://www.kaggle.com/datasets/fahmidachowdhury/customer-segmentation-data-for-marketing-analysis).
It contains the following attributes:
- **id**: Unique customer identifier.
- **age**: Age of the customer.
- **gender**: Gender of the customer (Male, Female, Other).
- **income**: Annual income of the customer (in USD).
- **spending_score**: Spending behavior and loyalty (scale of 1-100).
- **membership_years**: Years as a customer.
- **purchase_frequency**: Frequency of purchases.
- **preferred_category**: Most purchased category.
- **last_purchase_amount**: Amount spent on the most recent purchase (in USD).


## Methodology
1. **Data Preprocessing**
   - Scaled numerical features using StandardScaler.
   - Encoded categorical variables using One-Hot Encoding.

2. **Clustering**
   - Applied K-Means clustering and determined the optimal number of clusters using the Elbow Method and Silhouette Scores.
    
3. **Cluster Analysis**
   - Calculated the average values of features within each cluster.
   - Analyzed preferred categories and gender distributions for each cluster.

4. **Business Recommendations**
   - Derived insights for targeted marketing strategies for each customer segment.

## Results
### Cluster Characteristics Summary

1. **Cluster 0: Younger, Loyal Customers**
   - Younger males with moderate income and spending habits.
   - Loyal members (~6 years) with frequent purchases (~35).
   - Prefer home-related products (Home & Garden).

2. **Cluster 1: Middle-Aged, High-Income Customers**
   - Middle-aged females with high income and selective spending.
   - Less frequent shoppers (~18 purchases) but focus on premium items like Electronics and Home & Garden.
   - Shorter membership duration (~4.8 years).

3. **Cluster 2: Older, High-Spending Customers**
   - Older and diverse group with lower income but high spending behavior.
   - Moderate loyalty (~5.5 years) and focus on essential goods (Groceries).
   - Spend more on fewer purchases (~27).
  
## Technologies Used
- **Programming Language**: Python
- **Libraries**: pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Acknowledgments
- Dataset sourced from Kaggle. Find it [here](https://www.kaggle.com/datasets/fahmidachowdhury/customer-segmentation-data-for-marketing-analysis).
- Special thanks to [Esther Anagu](https://estheranagu.medium.com/customer-segmentation-for-marketing-analysis-project-8a93d841b812) for providing valuable insights that guided the clustering methodology.

## Conclusion
By leveraging clustering insights, businesses can unlock the potential of personalized marketing, ensuring long-term growth and customer satisfaction.

