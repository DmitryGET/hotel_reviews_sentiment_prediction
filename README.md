# hotel_reviews_sentiment_prediction
📚Dataset📚:

https://www.kaggle.com/andrewmvd/trip-advisor-hotel-reviews

📋Description📋: 

In this task, I decided to analyze the problem of binary classification: what is the mood of a hotel review-positive or negative? Since I will have to work with text data, I decided to use transformers, namely BERT, to tokenize the text and convert it to numeric data. Next, I built a simple neural network for predictions and fed it the data transformed by BERT

🎯Target🎯: 

Creating a model that will determine the sentiment of a hotel review (positive or negative sentiment)

⚙️Used technologies⚙️:

◾pandas

◾matplotlib

◾sklearn

◾transformers (DistilBertTokenizer, TFDistilBertModel)

◾tensorflow

📈Metric📈: 

F1 Score

🎉Result🎉: 

F1 Score == 0.95

