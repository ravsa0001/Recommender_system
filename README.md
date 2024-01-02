## _Recommendation System_

The recommendation system is designed to provide personalized recommendations to user based on content-based and collaborative filtering methods. By leveraging both approaches, 
the system aims to enhance the accuracy and diversity of recommendations, addressing the limitations of each method individually.

## Features
1) **Content-based filtering**
    - Utilizes features such as item descriptions, genres, and user preferences to make recommendations.
    - The model calculates similarity between items and users using **cosine similarity**.

2)  **Colaborative filtering**
    - Utilizes user-item interaction data, such as user ratings or purchase history, to identify patterns and recommend items to users with similar preferences.
    - Utilizing KNN helps in identifying similarities between users based on their interactions.

## Dependencies
- python(>3.6)
- pandas
- scikit-learn
- scipy
- numpy
- fuzzywuzzy
