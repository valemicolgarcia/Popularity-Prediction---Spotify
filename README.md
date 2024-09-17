# Youtube Song Likes Prediction
 
This project aims to predict the number of likes that a song's video receives on YouTube. The prediction is based on a dataset containing 28 variables related to Spotify, YouTube, and specific musical composition features. Using Linear Regression, the model identifies key factors that influence the popularity of a song’s video.Se tiene la intención de entrenar un algoritmo para detectar cuáles son los factores que influyen en el número de likes que tiene el video de una canción en youtube. El objetivo es predecir este número basándose en diferentes características. 

### Project Overview
The primary goal is to analyze which attributes contribute to the number of likes on a video of a song, such as energy, danceability, and other musical features. By training a predictive model, we can estimate how these characteristics affect user engagement on YouTube.
**Modelo: Regresión Lineal**

# Workflow

### 1. Analytical Goal and Context
Define the project's objective and provide the business or research context.
### 2. Data Acquisition
Import the dataset containing features from Spotify and YouTube.
### 3. Null Value Treatment
Handle any missing values within the dataset.
### 4. Outlier Handling
Address outliers to improve model accuracy.
### 5. Encoding and Scaling
Prepare categorical and numerical variables for modeling.
### 6. Exploratory Data Analysis (EDA)
Visualize trends, distributions, and relationships between variables.
### 7. Model Training
Train a Linear Regression model to predict video likes.
### 8. Metrics Evaluation
Measure model performance using appropriate metrics.
### 9. Cross-Validation
Validate the model to ensure generalization to unseen data.


# Setup
To run the project locally, install the required Python libraries:

```
pip install pandas matplotlib seaborn numpy scikit-learn
```

Clone the repository and launch the Jupyter notebook:
```
git clone https://github.com/yourusername/youtube-song-likes-prediction.git
cd youtube-song-likes-prediction
jupyter notebook prediction.ipynb

```

