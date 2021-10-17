# Predicting-the-charges-of-insurance using Linear Regression 

In this repository, I have used Linear Regression model to predict how much a person would be charged for insurance according to several features such as age, region they lived in, bmi etc...

Since there were no null values, there was no cleaning to be done however because the data in table had categorical values such as 'male' and 'female' in the sex feature and also in the regions feature, I created dummies in the dataset seperately for each of the categorical inputs. They were labelled with either 0 or 1.

After the processing of the data was complete, I used the train_test_split function to seperate the training and testing data, keeping the test size to be 20% of the entire dataset. Then I fit the data into Linear Regression from sklearn for prediction. 

From running the model, I had achieved a r2 score of 0.799987 (approximately 80% accuracy)




