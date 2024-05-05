# Movie-Recommendation-With-Models
This analysis uses the rating distribution, the correlation between the timestamp and ratings, and the segmentation of users based on their mean ratings to identify trends and patterns in movie ratings and user behavior.

The Link to the Dataset: https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset

☙**Background**

The dataset used in this analysis is a movie rating dataset, which contains ratings given by users to various movies. The goal of this analysis is to explore the distribution of movie ratings, identify patterns and correlations, and gain insights into user behavior.

🛢️**Dataset Description**

The dataset consists of three columns: userId, movieId, and rating. The userId column represents the unique identifier for each user, the movieId column represents the unique identifier for each movie, and the rating column represents the rating given by the user to the movie. The timestamp column, which represents the time when the rating was given, was initially included but was later dropped due to a lack of correlation with the rating.

🔑**Key Findings and Insights**

1. Rating Distribution: The rating distribution is skewed to the right, with most ratings falling between 2.2 and 4.5. The peak density curve is at 1.2, indicating that most ratings are positive.
2. Positive Correlation between Timestamp and Ratings: There is a positive correlation between the timestamp and ratings, suggesting that as time goes on, the average movie rating increases. This could be due to selection bias, where newer movies are more popular or anticipated, or rating inflation, where moviegoers tend to give out higher ratings over time.
3. User Behavior: The analysis of users with the lowest and highest mean ratings reveals distinct patterns. Users with low mean ratings tend to give lower ratings overall, while users with high mean ratings tend to give higher ratings. This suggests that users have different rating patterns and preferences.
4. User Segmentation: The KDE plots for users with low and high mean ratings show that users can be segmented based on their rating behavior. This segmentation can be useful for personalized recommendation systems or targeted marketing campaigns.
   
🔎**Insights**

1. Rating Inflation: The positive correlation between timestamp and ratings suggests that rating inflation may be a factor in the dataset. This could be due to changes in user preferences or the increasing quality of movies over time.
2. User Preferences: The analysis of user behavior and rating patterns suggests that users have different preferences and biases when it comes to rating movies. This could be used to develop more accurate recommendation systems or to identify niche audiences.
3. Movie Quality: The rating distribution and user behavior suggest that movie quality may be improving over time, leading to higher ratings. This could be due to advances in filmmaking technology, changes in audience preferences, or the increasing popularity of certain genres.

📝**Recommendations**

1. Control for Rating Inflation: To account for rating inflation, it may be necessary to adjust the rating scale over time or to use a more robust rating system.
2. Personalized Recommendations: The segmentation of users based on their rating behavior could be used to develop more accurate and personalized recommendation systems.
3. Movie Quality Analysis: Further analysis of the dataset could be used to identify trends in movie quality and to develop more accurate metrics for evaluating movie performance.
