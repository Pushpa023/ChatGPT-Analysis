# ChatGPT-Analysis
Project Overview:
This project analyzes a dataset of ChatGPT reviews to understand user sentiment, identify trends over time, and explore common issues based on user feedback.

Project Structure:
The project is structured as a Jupyter Notebook (or Google Colab notebook) containing the code and analysis steps. Key sections include:

Data Loading and Cleaning
Sentiment Analysis
Sentiment Trend Analysis
Ratings vs. Sentiment Analysis
Review Length Analysis
Common Issue Identification (Negative/Low-Rated Reviews)

Data:
The analysis uses the chatgpt_reviews.csv dataset, which contains review text, ratings, and review dates.

Steps Performed:
Data Loading and Cleaning: Loaded the chatgpt_reviews.csv file into a pandas DataFrame. Cleaned the data by handling missing values in the 'review' column, standardizing column names, and converting 'review_date' and 'ratings' to appropriate data types.

Sentiment Analysis: Applied TextBlob to the 'review' column to calculate polarity and classify reviews into 'positive', 'neutral', and 'negative' sentiments.

Sentiment Trend Analysis: Extracted year and month from 'review_date', grouped the data by time and sentiment, and visualized the sentiment counts over time using a line plot with legends and grid lines.

Ratings vs. Sentiment Analysis: Grouped the data by sentiment and calculated the average rating for each sentiment category, displaying the results and visualizing them with a bar plot.

Review Length Analysis: Calculated the length of each review, displayed descriptive statistics for review lengths, and visualized the distribution using a histogram with grid lines.

Common Issue Identification (Negative/Low-Rated Reviews): Filtered the DataFrame to include negative and low-rated reviews and began preprocessing the text (removed punctuation, converted to lowercase, removed stop words).
