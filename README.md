# RECOMMENDATION-SYSTEM

COMPANY NAME:CODTECH IT SOLUTIONS

INTERN NAME:JUNAIDA ADAKANDY MOIDU

INTERN ID:CT06DG1194

DOMAIN NAME:MACHINE LEARNING

DURATION:6 WEEKS

MENTOR:NEELA SANTHOSH

DESCRIPTION:
As part of my internship, Task 4 involved the development of a Recommendation System using Collaborative Filtering and Matrix Factorization techniques. Recommendation systems are among the most widely used machine learning applications in real-world platforms, such as Netflix, Amazon, YouTube, Spotify, and many more. The objective of this task was to build a movie recommendation engine that predicts what movies a user might like based on their previous ratings and the behavior of similar users.

Tools and Environment Used
For the development and implementation of this task, I used the following:

Editor/IDE: Jupyter Notebook
Jupyter Notebook is a widely used open-source web application that allows the creation and sharing of live code, equations, visualizations, and narrative text. It was the ideal environment for this task due to its interactivity and ease of use in data science workflows.

Programming Language: Python
Python was used due to its simplicity and the vast array of libraries it offers for data analysis and machine learning.

Libraries/Frameworks:

pandas for data loading and preprocessing

scikit-surprise (also called surprise) for building collaborative filtering models like SVD (Singular Value Decomposition)

matplotlib and accuracy module from surprise for evaluation metrics such as RMSE and MAE

Dataset Used
For this project, I utilized the MovieLens 100k dataset, which contains 100,000 ratings by 943 users on 1682 movies. This dataset is widely used for benchmarking recommendation systems and was suitable for faster training and evaluation compared to larger datasets like MovieLens 20M or 32M.

The dataset consists of:

User IDs

Movie IDs

Ratings (on a scale of 1 to 5)

Movie metadata (like titles)

I loaded and preprocessed the dataset using pandas, and then formatted it according to the requirements of the surprise library using its Reader and Dataset classes.

Methodology
Data Preparation:
I started by importing the necessary libraries and reading the MovieLens 100k dataset into a DataFrame. Unnecessary columns such as timestamps were removed.

Model Selection:
I selected the SVD (Singular Value Decomposition) algorithm from the surprise library. SVD is a popular matrix factorization technique that reduces the dimensionality of the user-item rating matrix and captures latent features of both users and items.

Training and Testing:
The dataset was split into training and testing sets using train_test_split. The model was trained on the training set and then used to make predictions on the test set.

Evaluation:
The accuracy of the recommendation system was evaluated using RMSE (Root Mean Square Error) and MAE (Mean Absolute Error). These metrics help assess how close the predicted ratings are to the actual ratings.

Generating Recommendations:
After predictions were made, I extracted the top 5 movie recommendations for each user using the get_top_n() function. These recommendations were mapped to movie titles and displayed in a readable format.

Exporting Results:
I also exported the recommendations to a .csv file for submission or further analysis.

Real-World Applications
This recommendation system project simulates the core functionality of popular streaming and e-commerce platforms. Such systems are used to:

Improve user experience by showing personalized content

Increase user engagement and retention

Generate higher revenue through relevant suggestions

Reduce content discovery time for users

Collaborative filtering, especially matrix factorization methods like SVD, has proven to be highly effective in recommendation tasks and forms the backbone of many production-grade systems.

Conclusion
Through this project, I successfully implemented a collaborative filtering-based recommendation system from scratch. I used the surprise library for its powerful tools in building and evaluating recommendation models. The project enhanced my understanding of user-item interactions, matrix factorization, and the real-world challenges involved in recommender systems.

This task not only strengthened my Python and data science skills but also helped me understand how machine learning is applied to personalization systems used across industries.
