# Netflix Show and Movie Success Predictor 

## About

This is a mini-project developed for the SC1015 (Introduction to Data Science and Artificial Intelligence) course. The project focuses on analyzing movies from Kaggle that accessed and extracted data from Internet Movie Database (IMDB) and The Movie Database (TMDB).

## Walkthrough

The project consists of the following components:

1. **Data Extraction**: Extraction of movies' and TV shows' data from IMDB and TMDB.
2. **Data Resampling and Splitting**: Resampling and splitting of the data into `Movie` and `Show` tables for model training.
3. **Data Visualization and Analysis**: Visual representation of the extracted data and analysing correlations between the features.
4. **Neural Network**: Development of a neural network model for predicting movie quality.

#### Our Dataset: [Netflix TV Shows and Movies](https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies/data)

## Contributors

- @dayuhnah: Data Preparation & Cleaning (Data Extraction and Data Resampling), Data Analysis and Visualization
- @Migochii: Predictive Model (Neural Networks and Model Training), Data Analysis and Visualization

## Problem Definition
In the digital age, streaming services like Netflix have transformed entertainment consumption, offering unparalleled convenience and a diverse array of content. Netflix's expansive library spans genres and languages, catering to a broad audience. With the surge in on-demand viewing, Netflix has emerged as a leading platform, enabling users to enjoy a personalized entertainment experience at their convenience. This shift underscores a trend towards accessible and tailored entertainment, cementing Netflix's position as a cornerstone of the global digital entertainment landscape. However, with various of movies or TV shows being produced every year, how do producers know whether their movie/tv show idea will be popular or successful? Are they willing to risk precious materials and time to film it without knowing its success rate? What would assist them better in decisions and film making? 

Hence, the main objectives of the project are to develop a Predictive Model that can accurately determine the success or popularity of a show or movie in Netflix.

## Models Used

The project utilizes the following model:

1. **Neural Networks**: Development of neural network models using 'TensorFlow'.

## Conclusion

Key findings and conclusions from the project:

- Predictive modeling is able to improve content suggestions, enhancing user engagement and satisfaction.
- Understanding success factors aids Netflix in allocating resources effectively, optimizing its content library.
- Production Countries, Documentations and PG-13 movies have the highest correlations with Total Ratings for movies to produce successful movies.
- Production Countries, Drama and TV-14 TV Shows have the highest correlations with Total Ratings for shows to produce successful shows.
- Neural Network Models are able to grasp patterns better compared to other predictive models.


## Learning Outcomes

The project provides insights into various concepts and techniques, including:

- Handling imbalanced datasets using resampling methods (One-Hot Encoding and Target Encoding)
- Implementing Neural Networks using Keras and Tensorflow.
- Utilizing MinMaxScaler() from sklearn.
- Collaborating using GitHub.

---

This README offers a summary of the project, outlining its goals, approaches, and main discoveries. For in-depth insights and code explanations, please refer to the individual source files available in the repository.
