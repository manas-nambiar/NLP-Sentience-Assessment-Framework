**Amazon Reviews Sentiment Analysis**

This Python script performs sentiment analysis on Amazon product reviews and visualizes the results. It uses two methods for sentiment analysis: VADER Sentiment Analysis and RoBERTa (a pre-trained transformer model). The program also includes data visualization components to explore the relationship between sentiment scores and star ratings.

**Description**
The program accomplishes the following tasks:

**Data Loading:** It loads Amazon product reviews from a CSV file located in Google Drive.

**Sentiment Analysis:**

VADER Sentiment Analysis: Utilizes NLTK's VADER sentiment analysis tool to calculate sentiment scores (compound, positive, neutral, and negative) for each review.
RoBERTa Sentiment Analysis: Employs a pre-trained RoBERTa model to predict sentiment scores for the reviews.
Data Visualization: It visualizes the dataset and sentiment analysis results using Matplotlib and Seaborn, including bar charts to show the distribution of star ratings and the relationship between sentiment scores and star ratings.

**Usage**
Upload your Amazon product reviews dataset in CSV format to your Google Drive.

Update the dataset_path variable in the script with the correct path to your dataset.

Execute the script in a Python environment.

**Dependencies**
- pandas
- numpy
- matplotlib
- seaborn
- nltk
- transformers
