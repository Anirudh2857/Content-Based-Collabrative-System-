This project implements a content-based recommendation system using the Netflix dataset. The system analyzes the similarity between movies based on their genres, release year and cast, and recommends similar movies to users.

**Dataset**

The dataset used in this project is the Netflix Prize dataset, which includes over 100 million movie ratings from around 480,000 users. The dataset was originally released as part of a competition by Netflix in 2006 to improve their recommendation system.

The dataset is not publicly available, but it can be obtained by signing up to the Netflix Prize competition website and agreeing to the terms of use.

**Approach**

The system implements a content-based approach to recommend movies to users. This approach analyzes the features of movies and recommends similar movies to users based on their past ratings and preferences.

The system first preprocesses the Netflix dataset by filtering out movies that have less than 100 ratings and users who have rated less than 10 movies. This reduces the size of the dataset and improves the quality of the recommendations.

The system then extracts the genres, release year and cast information from the movie titles using regular expressions. This information is used to create feature vectors for each movie, which are then used to compute the similarity between movies.

The similarity between movies is calculated using the cosine similarity metric, which measures the angle between two feature vectors. The closer the angle, the higher the similarity between the movies.

Finally, the system recommends similar movies to users based on their past ratings and preferences. The recommendations are ranked based on their similarity score and presented to the user.

**Conclusion**

This project implements a content-based recommendation system using the Netflix dataset. The system analyzes the similarity between movies based on their genres, release year and cast, and recommends similar movies to users. This approach can be useful in situations where there is limited user data available or where the recommendation system needs to be based on the characteristics of the items being recommended.
