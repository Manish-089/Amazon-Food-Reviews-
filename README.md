Amazon Food Reviews Analysis
This project aims to analyze a dataset of Amazon food product reviews to gain insights into customer sentiments, identify trends, and potentially improve product offerings based on feedback.

Project Overview
The notebook performs the following tasks:

Data Preprocessing: Loading, cleaning, and organizing the Amazon food reviews dataset.
Exploratory Data Analysis (EDA): Exploring patterns, trends, and relationships in the data through visualizations and summary statistics.
Sentiment Analysis: Using NLP techniques to classify customer reviews as positive or negative.
Modeling: Building machine learning models to predict the sentiment of reviews.
Model Evaluation: Assessing the performance of the machine learning models using appropriate metrics.
Dataset
The dataset contains food product reviews from Amazon, including the following columns:

ProductId: Unique identifier for the product
UserId: Unique identifier for the user who wrote the review
ProfileName: User profile name
Helpfulness: Helpfulness rating of the review
Score: Rating score given by the reviewer (1–5)
Time: Timestamp of the review
Summary: Short summary of the review
Text: The full text of the review

Libraries Used
The following Python libraries are used in the project:

Pandas: For data manipulation and analysis.
NumPy: For numerical computing and array operations.
Matplotlib: For generating visualizations and plots.
Seaborn: For enhanced data visualizations and aesthetic plots.
Scikit-learn: For machine learning models, including classification and model evaluation metrics.
NLTK (Natural Language Toolkit): For natural language processing tasks such as tokenization, stopword removal, and sentiment analysis.
WordCloud: To generate visual word clouds of the most frequently mentioned words in reviews.

Results
The project performs sentiment analysis on the reviews, identifying whether they are positive or negative. It also explores general trends in the dataset, such as:

Distribution of review ratings (1 to 5 stars)
Most frequently mentioned words in positive vs. negative reviews
Word clouds for visual representation of common terms
Performance of machine learning models like Logistic Regression, Random Forest, and others in predicting review sentiment.
