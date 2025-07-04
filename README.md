🌧️ Rain Prediction Using Logistic Regression
This project builds a Logistic Regression model to predict whether it will rain tomorrow based on historical Australian weather data. It demonstrates data preprocessing, model training, evaluation, and prediction.

🚀 Features
Preprocesses real-world weather data (handles missing values, scaling, and encoding).

Splits data into training, validation, and test sets.

Trains a logistic regression classifier using scikit-learn.

Evaluates performance using accuracy and confusion matrix heatmaps.

Saves the trained model and preprocessing steps for future use.

Supports making predictions on new input data.

🔧 Setup Instructions
Clone this repository:

git clone https://github.com/your-username/your-repo.git
cd your-repo

Install the required packages:
pip install -r requirements.txt

Download the dataset from Kaggle manually (weatherAUS.csv) and place it in the /weather-dataset-rattle-package/ folder.

Run the main Python file to train the model and generate predictions.

📊 Example Output
Accuracy: 84.5%
Confusion Matrix:
[Heatmap plot shown here]
Prediction for example input: ('Yes', 0.67)
