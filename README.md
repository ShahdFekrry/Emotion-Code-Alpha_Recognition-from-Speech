# Emotion-Code-Alpha_Recognition-from-Speech


# Dataset Preparation:

Mount Google Drive to access the RAVDESS dataset.
Read the dataset from Google Drive.
Parse emotion labels and file paths from the RAVDESS dataset.

# Exploratory Data Analysis (EDA):

Print a summary of the dataset.
Print the count of each emotion category.
Visualize the distribution of emotions using count plots and pie charts.

# Data Augmentation:

Generate modified versions of audio samples to increase the diversity of the dataset.
Apply noise, stretching, shifting, and pitch modifications to audio samples.

# Feature Extraction:

Define functions to extract features such as zero-crossing rate (ZCR), root mean square energy (RMSE), and Mel-frequency cepstral coefficients (MFCCs) from audio data.
Extract features from audio files, including augmented versions.

# Parallel Processing:

Utilize parallel processing to extract features from audio files efficiently.

# Data Preprocessing:

Handle missing values in the extracted features.
Split the dataset into features (X) and target labels (Y).
Perform one-hot encoding on the target labels.
Split the data into training and testing sets.
Scale the features using standardization.

# Model Training:

Train a multilayer perceptron (MLP) classifier using the training data.
Tune hyperparameters such as alpha, batch size, and maximum iterations for the MLP model.

# Model Evaluation:

Evaluate the trained model using the testing data.
Calculate the accuracy of the model.
Generate a classification report to assess precision, recall, F1-score, and support for each emotion category.

# Confusion Matrix Visualization:

Plot a confusion matrix heatmap to visualize the performance of the model.
Use seaborn to create a heatmap with annotated values representing the number of correct and incorrect predictions.
