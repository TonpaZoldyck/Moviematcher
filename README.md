## Movie Recommendation System

### Overview
In this project, I undertook the exciting challenge of developing a Movie Recommendation System, harnessing the power of data analytics and machine learning to elevate the movie-watching experience. With a rich dataset of user ratings at my disposal, I delved deep into the realms of collaborative filtering, cluster analysis, and PyTorch integration to provide personalized movie recommendations.

### Key Highlights
- **Exploratory Analysis:** The journey began with a thorough exploratory analysis of the dataset. I dived into the intricate world of movie ratings, uncovering valuable insights about user preferences, genre popularity, and temporal trends. This critical phase laid the foundation for the entire project.

- **PyTorch Integration:** To build and evaluate machine learning models, I seamlessly integrated PyTorch into the workflow. PyTorch's flexibility and deep learning capabilities proved invaluable in crafting and fine-tuning recommendation algorithms.

- **Data Preparation:** Handling raw data is a significant challenge in recommendation systems. I meticulously preprocessed the dataset, addressing missing values, encoding categorical features, and normalizing numerical data. Data preparation was a crucial step in ensuring the accuracy and reliability of our models.

- **Cluster Analysis:** Cluster analysis emerged as a pivotal component of the project. I applied sophisticated clustering techniques to segment users into seven distinct clusters. These clusters were formed primarily based on user ratings, providing a foundation for personalized recommendations.

- **Optimal Model Selection:** Through a rigorous evaluation process, I identified the Random Forest model as the optimal choice for our recommendation system. Its ability to handle complex data and deliver accurate predictions significantly enhanced the user experience.

### Analysis and results
![Clusters Image](/Unknown-2.png)

In our movie recommendation system, we applied K-means clustering with the elbow method to categorize users into distinct clusters based on their movie-watching behavior. This clustering approach helps us understand different segments of our audience, allowing us to provide more personalized movie recommendations.

**Cluster Summary**

We have identified a total of 7 distinct user clusters:

1. **Cluster 1**:
    - This is the second largest cluster, containing over 20,000 individuals.
    - Users in this cluster exhibit common movie-watching preferences and behaviors.
    - Recommendations tailored to this group should appeal to a wide audience.

2. **Cluster 2**:
    - Similar to Cluster 1, this cluster also includes over 20,000 individuals.
    - These users share common movie interests but may have some variations in their viewing habits.
    - Recommendations for this cluster should cater to popular movie tastes.

3. **Cluster 3**:
    - Cluster 3 is one of the rarer groups, with fewer than 5,000 individuals.
    - Users in this cluster have distinctive movie preferences.
    - Targeted recommendations should focus on niche content to engage this group effectively.

4. **Cluster 4**:
    - Like Cluster 3, this cluster is smaller, with fewer than 5,000 individuals.
    - These users exhibit unique movie-watching patterns, different from the larger clusters.
    - Personalized recommendations should account for these distinctive tastes.

Understanding these user clusters is crucial for tailoring movie recommendations to various audience segments, enhancing the overall user experience.


![Cluster Correlation_Image](/Unknown-3.png)

## Correlation Analysis - Movie Recommendation System

In our movie recommendation system, we performed a correlation analysis to understand how various features in the dataset relate to the user clusters created using K-means. This analysis provides insights into the factors influencing cluster definitions and offers guidance on personalized movie recommendations.

### Key Findings

**Negatively Correlated Features:**

- **Genre Types:** Notably, genres such as *Drama*, *Romance*, and *Crime* show negative correlations with certain user clusters. This suggests that users in these clusters tend to have less interest in movies from these genres.

- **Rating:** The rating given by users plays a significant role in defining user clusters. This is expected since we used ratings to create the clusters. Users in different clusters exhibit varying rating patterns.

- **Enjoyment:** The level of enjoyment expressed by users while watching a movie also contributes to cluster definitions. It's clear that users in different clusters have varying enjoyment preferences, influencing their cluster assignment.

**Positively Correlated Features:**

- **Movie ID and User ID:** Interestingly, the features "Movie ID" and "User ID" exhibit positive correlations with cluster definitions. This suggests that certain movies and individual users are closely associated with particular clusters. It could be that specific movies or user preferences strongly align with certain cluster characteristics.

The correlation analysis sheds light on the underlying factors that define our user clusters in the movie recommendation system. We find that genre types, ratings, and enjoyment levels have a significant impact on cluster assignments. This information is valuable for generating personalized movie recommendations for our users.

Additionally, the positive correlations between "Movie ID" and "User ID" and cluster definitions highlight the potential to further customize recommendations based on individual movie and user preferences within these clusters.

By leveraging these insights, we can enhance the user experience by providing tailored movie suggestions that align with the preferences and behaviors of each user cluster.


### Conclusion
The Movie Recommendation System project showcases my expertise in leveraging data analytics and machine learning to enhance user satisfaction. From in-depth exploratory analysis to seamless PyTorch integration and meticulous data preparation, every aspect of the project was meticulously executed. The successful implementation of cluster analysis underscored my commitment to delivering tailored recommendations based on individual user preferences. This project exemplifies my dedication to data-driven solutions that elevate user-centric applications.
