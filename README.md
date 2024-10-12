# Spam Email Detection

## Introduction

This project focuses on detecting spam emails using a dataset containing information from 5,172 randomly selected email files. The goal is to build a classification model that can accurately distinguish between spam and not-spam emails based on the content of the emails.

## About the Dataset

The dataset is provided in a CSV file with the following characteristics:

- **Rows**: 5,172 rows, each representing an individual email.
- **Columns**: 3,002 columns in total.
  - **First Column**: Indicates the email name. The names have been anonymized with numbers to protect privacy.
  - **Last Column**: Contains the labels for classification:
    - `1` for spam emails.
    - `0` for not-spam emails.
  - **Remaining 3,000 Columns**: These columns represent the 3,000 most common words across all emails, excluding non-alphabetical characters. Each cell in these columns contains the count of the respective word in the corresponding email.

This compact representation allows for efficient processing and analysis of email data without needing to work with separate text files.

## Objective

The goal of this project is to:

1. Understand and visualize the dataset.
2. Train a classification model to accurately predict the class of obesity based on the four features.
3. Evaluate the performance of different classification models using metrics such as accuracy, precision, recall, and F1-score.

## Steps Involved

1. **Data Exploration**:
   - Visualize the data to understand the distribution of features for each species.
   - Analyze the relationships between different features using scatter plots, pair plots, and correlation matrices.
   
2. **Data Preprocessing**:
   - Handle any missing values (though none are present in this dataset).
   - Split the data into training and testing sets for model evaluation.
   
3. **Model Training**:
   - Build and train classification the model using algorithms such as:
     - K Nearest Neighbors
   
4. **Model Evaluation**:
   - Evaluate the models using appropriate classification metrics:
     - **Accuracy**: Percentage of correctly classified instances.
     - **Precision**: The proportion of predicted positives that are actually positive.
     - **Recall**: The proportion of actual positives that are correctly predicted.
     - **F1-Score**: The harmonic mean of precision and recall.
     - **Confusion Matrix**: To visualize the true positives, false positives, true negatives, and false negatives.

## Model Performance Metrics

- **Accuracy**: Measures how often the classifier makes the correct predictions.
- **Precision and Recall**: Evaluate the performance when dealing with imbalanced classes (though this dataset is balanced).
- **F1-Score**: Useful when balancing precision and recall.
- **Confusion Matrix**: To visualize how well the model performed in each class.

## Project Structure

The project is organized as follows:

- `data/`: Contains the CSV file with email data for spam detection.
- `notebooks/`: Jupyter notebooks for data exploration, feature selection, model training, and evaluation.
- `models/`: Saved models and related artifacts.
- `README.md`: Project overview and documentation.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/arghads9177/spam-email-detection-knn.git

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or inquiries, please contact `Argha Dey Sarkar` at [email2argha@gmail.com].
