# Fake-News-Detection
This repository implements a Fake News Detection system using machine learning techniques. It preprocesses news articles and trains models to classify them as real or fake.
## Features
Data Preprocessing: Cleans and prepares the dataset for training.
Machine Learning Models:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Evaluation: Measures performance using accuracy and classification reports.
API Integration: (Optional) For real-time prediction capabilities.
## Dataset
The project uses two datasets:

Fake.csv: Contains fake news articles.
True.csv: Contains real news articles.

Each dataset includes the text of articles and their corresponding labels:

0: Fake news
1: Real news

## Installation
Clone the repository
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
Install the required dependencies
pip install -r requirements.txt
## Usage
Preprocess the data:

Load datasets: Fake.csv and True.csv.
Assign labels: 0 for fake and 1 for real.
Split into training and testing sets.
Train machine learning models:

Logistic Regression
Decision Tree
Random Forest
Evaluate the models:

Accuracy score
Classification report
(Optional) Use the provided API for real-time predictions.

## Results
The project evaluates models based on their accuracy and other performance metrics.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


