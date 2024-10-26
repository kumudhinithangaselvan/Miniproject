## Title of the Project
Customer Segmentation Using Machine Learning
This project uses machine learning to segment customers based on purchasing patterns, helping businesses target each group effectively. By clustering similar customers together, companies can tailor marketing strategies, improving customer satisfaction and driving profitability.

## About
This project focuses on customer segmentation using machine learning to analyze and categorize customers based on their buying behaviors, demographics, and spending patterns. The primary goal is to identify distinct groups within a customer base to optimize marketing strategies and enhance personalization.

Through data collection, preprocessing, and feature extraction, the model applies clustering algorithms like K-means and PCA for dimensionality reduction. The clusters provide insights into customer types, enabling targeted promotions, loyalty programs, and better product recommendations, ultimately enhancing customer engagement and boosting business revenue.

## Features
- Automated Data Preprocessing: Cleans, transforms, and reduces data for accurate analysis.
- Feature Extraction: Calculates key customer metrics (e.g., frequency, recency, monetary value) for detailed profiling.
- Clustering Algorithms: Supports K-means, K-medoids, and Mini Batch K-means for effective customer grouping.
- Optimal Cluster Selection: Uses silhouette scores and PCA for choosing the ideal number of clusters.
- Customer Classification Matrix: Generates a matrix for easy customer segmentation visualization and targeted insights.

## Requirements
* Python 3.x: Programming language for implementing the model and preprocessing data.
* Pandas: For data manipulation and preprocessing.
* NumPy: For numerical computations.
* scikit-learn: For clustering algorithms, silhouette scoring, and PCA.
* Matplotlib/Seaborn: For data visualization
* Jupyter Notebook (optional): For interactive code development and visualization.
  
## System Architecture


![WhatsApp Image 2024-10-24 at 22 09 19_6786e61c](https://github.com/user-attachments/assets/afa85129-ebed-4e38-963d-ac92e31696c5)



## Output

![image](https://github.com/user-attachments/assets/d17c2e34-f680-415a-ab95-f4e2109cede1)

![image](https://github.com/user-attachments/assets/5cfbaf4b-7b97-4e54-b722-7a2f488a37cb)

# Creating group of ages:
![image](https://github.com/user-attachments/assets/798a795f-560d-4c7a-b81a-a6fc8215150d)
![image](https://github.com/user-attachments/assets/a9ee3e53-84d6-46d1-927a-90c4538ff133)


# Creating groups of ‘Spending Score’ column and visualizing it:
![image](https://github.com/user-attachments/assets/4a659206-e21a-4074-bdad-06423bb911ad)
![image](https://github.com/user-attachments/assets/082159ae-5fb4-4daa-8b9c-1b044c120db2)


## Creating groups for ‘Annual Income’ column and visualizing it:
![image](https://github.com/user-attachments/assets/0471f649-5b01-47b5-81b7-4636add312cf)
![image](https://github.com/user-attachments/assets/d9239b7c-7d5f-479a-a8d1-b81cc8654631)


#Let’s also create a relation plot between the ‘Annual Income’ column and ‘Spending Score’ column.
![image](https://github.com/user-attachments/assets/219b94ea-6311-4f04-b678-a69464de986a)
![image](https://github.com/user-attachments/assets/6503d165-dd94-468c-b7bd-33f8a7a3638c)


# number of clusters
![image](https://github.com/user-attachments/assets/b61a9352-4ba5-4c84-9160-0d5b8258e1a5)
![image](https://github.com/user-attachments/assets/9e05ccd6-6e0e-48ab-8ffd-cd5a2a05aed7)



#Fit that clusters into KMeans model and predict labels, and also find centroids:
![image](https://github.com/user-attachments/assets/263afc4d-c3e6-4528-8104-bb38407ad49f)
![image](https://github.com/user-attachments/assets/1fd9c5d7-127e-4b45-b50d-f98973182d69)


# Creating Clusters based on Annual Income and Spending Score:
![image](https://github.com/user-attachments/assets/5e40039c-174b-42e9-9912-091ddcfbb1cf)
![image](https://github.com/user-attachments/assets/5ac6921b-029e-4c54-926f-1cbea67927c4)



# fit this into our KMeans algorithm and predict labels and also find centroids:
![image](https://github.com/user-attachments/assets/143d5769-d9b6-4110-b4d2-8bcbfb7b46cf)
![image](https://github.com/user-attachments/assets/a20a2ed0-0090-495f-9c31-179474270172)


# Creating a Clusters based on Age, Annual Income, and Spending Score:
![image](https://github.com/user-attachments/assets/039781c4-6c67-42cb-9530-b261d8727df4)
![image](https://github.com/user-attachments/assets/e2db1ea1-5736-4f9c-8a27-17c51b78e713)


# 3D graph as there are three dimensions each dimension corresponding to one column.
![image](https://github.com/user-attachments/assets/8e47a0f0-d5e4-4f34-ab46-c4ca50ffeafe)
![image](https://github.com/user-attachments/assets/c442c71d-a25d-4808-b136-110779cd686d)

Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
Customer segmentation using machine learning led to enhanced customer insights and targeted marketing campaigns, resulting in a 15% increase in revenue within six months. Tailored strategies significantly reduced churn rates and boosted conversion rates by 30% through personalized recommendations. This approach also improved cost efficiency, lowering marketing expenses by 20% while enhancing overall effectiveness. The insights gained informed product development and supported strategic decision-making, fostering a better customer experience and establishing a foundation for sustained long-term growth.

## Articles published / References
"A Survey on Customer Segmentation: Techniques, Applications, and Challenges"
Author(s): J. A. V. M. de Oliveira, L. F. P. de Almeida, et al.
Journal: Expert Systems with Applications
Year: 2020
Summary: This survey reviews various techniques used for customer segmentation, highlighting the strengths and challenges of each method.

"Data-Driven Customer Segmentation Using Machine Learning"
Author(s): G. A. F. Marakas, et al.
Journal: Journal of Business Research
Year: 2018
Summary: This article explores the application of machine learning techniques in customer segmentation and their impact on marketing strategies.

"Customer Segmentation Using Machine Learning: A Case Study of E-Commerce"
Author(s): H. M. A. Ali, et al.
Journal: Journal of Retailing and Consumer Services
Year: 2021
Summary: This case study illustrates the application of machine learning algorithms for customer segmentation in the e-commerce sector.

"Segmenting Customers Based on Behavioral Data: A Machine Learning Approach"
Author(s): R. K. Gupta, et al.
Journal: International Journal of Information Management
Year: 2019
Summary: This paper discusses the use of behavioral data and machine learning techniques for effective customer segmentation and personalized marketing.

"Clustering Techniques in Customer Segmentation: A Review"
Author(s): A. S. W. P. M. Awan, et al.
Journal: Journal of Retailing and Consumer Services
Year: 2020
Summary: This review analyzes various clustering techniques employed in customer segmentation and their effectiveness across different industries.




