# BinaryClassification
## 	:warning: Disclaimer
This is a continuation of the [Sentiment Analysis](https://github.com/BryceDecker/SentimentAnalysis) project. Therefore, our motivation has been established and the data is ready for analysis. 

## 🛈 Background Information
Binary classification is a machine learning technique used to categorize data into two distinct classes or categories. It has been extensively applied in various domains, including spam detection, disease diagnosis, sentiment analysis, and fraud detection. By leveraging historical data and training algorithms, binary classification models are able to make predictions and classify new instances into one of the two predefined classes with high accuracy.

## 🎯 Aim
This project's focus will be on binary classification techniques to predict Lebron's response tone as either more neutral or more positive. We seek to identify models with the highest accuracy across various random states. 

## 📁 Datasets
[Interview data](https://github.com/BryceDecker/InterviewAnalysis/blob/main/Data_sets/clean/Interview_analysis_final.csv)

## :children_crossing: Walkthrough 

## :closed_book: Conclusion
With our data set on the smaller size we identified logistic regression (LR) and SVC as viable techniques. To identify the best performing binary classification method, we tested eight different techniques. Among them, Support Vector Classifier (SVC), Logistic Regression (LR), and K-Nearest Neighbors (KNN) consistently emerged as our top-performing methods. When evaluating results on different random states (for test-train-split), we identified a trend between test data which had larger amounts of 'more positive' data points and better the accuracy on the test data set. Ultimatively, we saw accuracy ranging from 70% up to 90%+ on the train and test data. For our random state (= 2), we obtained 80.95% accuracy using our LR and KNN models and 76.19% accuracy using the SVC model on our test data. These values are in excess of 25% more accurate than choosing 'more positive' every time and given our limitations on features (due to practice interviews having no associated statistics unlike post-game interviews) we find these results to be fairly strong.

## :construction: Improvements

We are aware that removing practice interviews from the data would yield much higher accuracy scores, as we identified in the Sentiment Analysis project. Being able to include game stats could offer further improvements through identifying additional impactful features.

More data, more data, more data.
