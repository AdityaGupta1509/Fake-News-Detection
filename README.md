# Fake-News-Detection

Welcome to the README file for our Fake News Detection project!

<h2>Project Overview</h2>
This is a machine learning project for detecting fake news articles. 
The model is trained on a dataset of news articles labeled as either "Fake" or "True" and uses natural language processing 
techniques to identify patterns and features that distinguish the two types of articles. 
The project consists of three main components: data preprocessing, model training, and model evaluation.

<h2>Data Preprocessing</h2>
The dataset used for this project is sourced from Kaggle, which consists of {"title", "text", "subject", "date"}. 
The dataset is preprocessed by Vectorization and also I created a function to convert the text in 
lowercase, remove the extra space, special chr., ulr and links.

<h2>Model Training</h2>
The models used for this project are [Logistic Regression, Random Forest Classifier, Decision Tree Classifier, Gradient Boosting Classifier], 
which are chosen because of their effectiveness in handling text data. 
The model is trained on the preprocessed dataset using [pandas, numpy, seaborn, matplotlib, sklearn].


<h2>Model Evaluation</h2>
We will create 1 column name "class" to help us evaluate the performance
We will evaluate the performance of our model using the code "LR.score(xv_test, y_test)"where "xv_test" is the output we got and "y_test" is the output needed. 
Additionally, classification report are generated to provide more detailed information on the model's performance

<h2>Usage</h2>
To use the fake news detector, run the Fake_news_detection.ipynb script and input the text of the news article you want to classify. 
The script will output a prediction of whether the article is "Fake News" or "Not A Fake News" using all the models used in this project.

<h2>Conclusion</h2>
Overall, this project demonstrates the potential of machine learning in detecting fake news articles. 
With further development and improvements, this technology can be a powerful tool in combating misinformation and promoting media literacy.
