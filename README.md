## Education Sentiment Analyser - AI class project

#Introduction
The Sentiment Analyzer is a machine learning-based application designed to classify the sentiment of text data, specifically focusing on educational content. It uses a pre-trained model from the Hugging Face library to predict sentiment categories such as very positive, positive, neutral, negative, and very negative.

#Features
Sentiment Classification: Analyzes text and categorizes it into one of five sentiment classes.
Pre-trained Model: Utilizes a BERT-based model for robust sentiment analysis.
Data Visualization: Includes functionality to visualize the distribution of sentiments in the dataset.

#Fine-Tuning and Perfomance
The model was fine-tuned on a dataset of course feedback collected from various sources. The data was pre-processed and split into training (80%) and validation (20%) sets. The BERT model was trained for three epochs with a batch size of 8, and the following evaluation metrics were used:
Accuracy: 97.6%
Precision: 0.976
Recall: 0.976
F1 Score: 0.976
These performance metrics indicate a fairly good performance given that this is multi-class classification which is generally less accurate than sentiment analysis with two categories (negative and positive).

