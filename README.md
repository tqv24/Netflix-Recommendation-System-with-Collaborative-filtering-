# Netflix Movie Recommendation System
## Overview
This project focuses on building a movie recommendation system for Netflix using collaborative filtering and Pearson's R correlations. The dataset utilized is sourced from the Netflix Prize Data, containing movie ratings provided by users.

## Project Structure
The project is organized into several sections:

1. Import Libraries
Essential Python libraries are imported for data manipulation, visualization, and collaborative filtering using the Surprise library.

2. Data Loading and Exploration
The movie titles dataset is loaded to explore the available movie information. Subsequently, individual movie rating datasets are loaded and cleaned.

3. Exploratory Data Analysis (EDA)
An analysis of the rating distribution is conducted through the use of a countplot, providing insights into the prevalence of different ratings.

4. Data Reduction
To handle the large dataset efficiently, data reduction techniques are applied. Movies with too few reviews and customers who give too few reviews are excluded to improve efficiency and statistical significance.

5. Collaborative Filtering
Collaborative filtering is implemented using the Surprise library. The SVD algorithm is employed to predict user ratings based on their historical preferences.

6. Movie Recommendation
Movies are recommended for a specific user (ID: 785314) using collaborative filtering. The recommendation is personalized based on the user's historical ratings.

7. Movie Recommendation with Pearson's R Correlations
A recommendation function is introduced based on Pearsons' R correlations. Users can input a movie title, and the system provides the top 10 recommended movies with the highest correlations.

Feel free to experiment with different movie titles, user IDs, and parameters to explore personalized recommendations.
