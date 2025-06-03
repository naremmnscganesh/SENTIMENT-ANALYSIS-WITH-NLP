# SENTIMENT-ANALYSIS-WITH-NLP


Movie Review Sentiment Analysis
**Overview**
This project implements a sentiment analysis system for the IMDB dataset of 50,000 movie reviews. Using Natural Language Processing (NLP) techniques including TF-IDF vectorization and logistic regression, the system classifies reviews as positive or negative with high accuracy.
**Dataset**
The project uses the IMDB Dataset of SOK Movie Reviews available on Kapgle:

**Requirements**
Core packages:

pandas numpy matplotlib seaborn scikit-learn

Optional packages: nltk wordcloud

**Installation & Setup**
1.	Clone this repository
2.	lnstal required packages:
3.	install optional packages:
4.	Download NLTK resources (if using): import nltk nltk.download('punkt') nltk.download('stopwords') nltk.download('wordnet')
5.	Download the IMDB dataset from Kagple and place in project directory
6.	Run the notebook:

**Pipeline Components
1.	Data Preprocessing**
•	Text cleaning (HTML/URL removal, lowercase conversion)
•	Stopword removal
•	Lemmatization
•	Robust fallbacks for missing dependencies

**2.	Feature Engineering**
•	TF-IDF vectorization with optimized parameters
 
•	N-gram features (unigrams and bigrams)

**3.	Model Building & Evaluation**
•	Logistic regression classifier
•	Accuracy, precision, recall, and F1-score reporting
•	Confusion matrix visualization
•	Feature importance analysis

**4.	Visualizations**
•	Sentiment distribution plots
•	Word clouds for positive and negative reviews
•	Feature coefficient visualization

**Error Handling**
The notebook includes robust error handling to ensure it runs successfully even with missing dependencies:
•	Alternative text processing methods if NLTK is unavailable
•	Fallback stopword lists and simplified stemming
•	Skip-ahead functionality for non-critical components

**Results**
The logistic regression model achieves strong classification performance. Feature importance analysis reveals key words and phrases that strongly correlate with each sentiment category, providing insight into the linguistic patterns associated with positive and negative movie reviews.

**Acknowledgments**
•	The IMDB dataset providers
•	The scikit-learn, NLTK, and WordCloud libraries
This project demonstrates a complete machine learning pipeline for text classification, from data preprocessing through model evaluation and interpretation. The robust error handling mechanisms ensure the analysis can run in various environments, making it accessible to users with different system configurations.

**output:-**
