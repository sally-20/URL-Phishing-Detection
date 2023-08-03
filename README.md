# Phishing Website Detection with Random Forest
This Colab notebook demonstrates how to build a phishing website detection model using the Random Forest algorithm. The model can be used to predict whether a given website is phishing or legitimate.

## Data
The dataset used in this notebook contains URLs along with their corresponding labels (phishing or legitimate). The dataset has been taken from Kaggle and is available at [Phishing Site URLs Dataset](https://www.kaggle.com/datasets/taruntiwarihp/phishing-site-urls). It consists of two columns: 'URL' containing the website URLs and 'Label' containing the corresponding labels ('phishing' or 'legitimate').

## Preprocessing
Before training the model, the URLs are preprocessed to extract their domain information using regular expressions. The extracted domains are used as input features for the model. One-hot encoding is also performed for the categorical input features.

## Training
A Random Forest classifier is created and trained on the preprocessed dataset. The model is evaluated for accuracy on the training set.

## Prediction
Once the model is trained, it can be used to predict whether a given URL is a phishing website or not. The user can input a URL, and the model will classify it accordingly.

### How to Use the Notebook
1. Data Download: Download the dataset from the [Phishing Site URLs Dataset](https://www.kaggle.com/datasets/taruntiwarihp/phishing-site-urls) on Kaggle.
2. Load the dataset: Upload the downloaded dataset containing URLs and their corresponding labels ('phishing' or 'legitimate'). Ensure that the dataset is in CSV format and has columns labeled 'URL' and 'Label'.
3. Run the code: Execute each code cell sequentially to preprocess the data, train the Random Forest model, and define the prediction function.
4. Prediction: When prompted, enter the URL you want to check if it's phishing or legitimate. The model will then provide the prediction result.

Thank you for using this Colab notebook for phishing website detection with Random Forest!
