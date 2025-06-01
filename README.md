# RECOMMENDATION-SYSTEM

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: AISHWARYA MULE

*INTERN ID*: CT12WV90

*DOMAIN*: MACHINE LEARNING

*DURATION*: 12 WEEKS

*MENTOR*: NEELA SANTOSH

##Collaborative Filtering Based Recommendation System

Project Overview

This project implements a movie recommendation system using collaborative filtering with Singular Value Decomposition (SVD), developed using the scikit-surprise library. The system is trained on the MovieLens 100k dataset, a well-known benchmark dataset in the recommender systems domain.

The objective is to build a model that analyzes historical user-item interactions (movie ratings) and provides recommendations for items the user has not yet rated. By identifying patterns in user preferences, the model suggests movies that the user is likely to enjoy.



Key Features

1. Collaborative filtering using implicit feedback and historical interactions.


2. Matrix factorization with the SVD algorithm to estimate unknown ratings.


3. Evaluation of the model using standard metrics such as RMSE and MAE.


4. Extraction and display of top-N movie recommendations for a sample user.


5. Compact and efficient implementation using Google Colab and Python libraries.



Technologies Used:

Python 3

scikit-surprise

NumPy

Google Colab


Dataset Used:

MovieLens 100k

100,000 ratings from 943 users on 1,682 movies

Ratings are on a scale from 1 to 5

Dataset is built into the surprise library (no manual download needed)


Evaluation Metrics:

Root Mean Squared Error (RMSE): Measures the square root of the average of squared differences between predicted and actual ratings.

Mean Absolute Error (MAE): Measures the average absolute difference between predicted and actual ratings.


These metrics are used to validate the model's prediction accuracy on the test data.


Sample Results:

After training the model and testing it on 20% of the dataset, the results were:

RMSE: approximately 0.94

MAE: approximately 0.74


These results indicate a reasonable prediction performance for a basic recommendation model.


Sample Output:

Example of top 5 movie recommendations for a user:

Top 5 recommendations for user 196:
Movie ID: 50, Estimated Rating: 4.63
Movie ID: 181, Estimated Rating: 4.59
Movie ID: 174, Estimated Rating: 4.56
Movie ID: 79, Estimated Rating: 4.55
Movie ID: 173, Estimated Rating: 4.52


How to Run

1. Open the notebook in Google Colab.


2. Ensure you run the first cell to install the correct package versions (scikit-surprise and compatible NumPy version).


3. Run all other cells sequentially.


4. View performance metrics and sample recommendations.



Future Improvements

Add support for other algorithms like KNNBasic, SVD++, or BaselineOnly.

Implement user/item similarity visualization.

Extend the system with a Streamlit or Flask frontend for real-time recommendations.

Integrate with a larger and real-world dataset for production use.


#OUTPUT

![Image](https://github.com/user-attachments/assets/48d65542-e7e0-45e3-ac38-6fd1b86ee4f2)
