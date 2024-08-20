# Sentiment-Analysis-
Machine Learning: Supervised Learning Final
Sentiment Analysis of Amazon Product Reviews
Project Overview

This project centers on performing sentiment analysis on Amazon product reviews, with the primary objective of classifying customer feedback as either positive or negative. Sentiment analysis is a fundamental task in natural language processing (NLP) that empowers businesses to gain insights into customer opinions and satisfaction levels through textual feedback. Understanding sentiment allows businesses to make informed decisions that enhance customer satisfaction and improve products and services.
Problem Statement

In this project, sentiment analysis is framed as a binary classification problem, aiming to categorize the sentiment expressed in customer reviews into two distinct categories: positive (indicating customer satisfaction) and negative (indicating dissatisfaction). This binary classification provides a clear and actionable understanding of customer sentiment, enabling businesses to identify strengths and weaknesses in their products or services.
Methodology

The project employs supervised learning, a machine learning approach where the model is trained on a labeled dataset of Amazon product reviews. Each review in the dataset is labeled as positive or negative based on the associated star rating. The dataset underwent several preprocessing steps to ensure data quality, including:

  Handling Missing Values: Missing data in critical columns (review_body and star_rating) were removed to maintain data integrity.
  Removing Duplicates: Duplicate reviews were eliminated to prevent redundancy and bias.
  Text Preprocessing: Standardizing the text format through case normalization, character removal, and stopword elimination, improving the accuracy of sentiment classification.

Two machine learning models were applied: Logistic Regression and Naive Bayes. These models were chosen for their simplicity and effectiveness in text classification tasks.
Results and Discussion

The results of the sentiment analysis indicated that the majority of Amazon reviews could be reliably classified into positive and negative sentiments using the chosen models. The analysis also highlighted the potential bias introduced by different types of reviews, such as those from the Amazon Vine program, which could affect the sentiment expressed.
Applications

This sentiment analysis has practical applications in various business contexts. By understanding customer sentiment, businesses can:

  Improve Products and Services: Address issues highlighted in negative reviews and reinforce aspects appreciated in positive reviews.
  Enhance Customer Satisfaction: Make data-driven decisions to improve customer experience, leading to increased customer loyalty.
  Stay Competitive: Use sentiment analysis as a tool to remain responsive to customer feedback and maintain a competitive edge in the market.

Conclusion

The sentiment analysis conducted in this project provides valuable insights into customer opinions as expressed in Amazon product reviews. The models developed offer a reliable method for classifying sentiment, which can be utilized by businesses to improve customer satisfaction and product offerings.
