# Digital-signal-processing-in-a-smartwatch

This repository is created in order to demonstrate the results of my research within the course Digital Signal Processing. 

The aim of this project is to use data obtained from the sensors fo a smartwatch in order to draw conclusions about the user's activities by applying the appropriate machine learning algorithms. 

![image](https://github.com/AHromic1/Digital-signal-processing-in-a-smartwatch/assets/115954313/d31d70a8-a6a9-4cdf-8461-5ae6c9401147)

The first part of the project included researching the topic in detail, and covering the theoretical part before the practical one (can be found under "Research").

And then, for the good part, I created, trained and tested the data from a smartwatch, previously divided into test (70%, however it cannot be found in this repository due to its large size) and train (30%) folders. There were six activities in total being recorded and differentiated between: walking, walking upstairs, walking downstairs, standing, sitting and laying down (code can be found in "Implementation/HARDataset/UCI HAR Dataset/Implementation.ipynb."). 

Having analysed the dataset, I was then able to apply different classificators and compare the results using confusion matrices. I used Logistic Regression, Support Vector Machine, Linear Discriminant Analysis, Random Forest Algorithm and Decision Tree Algorithm. After the comparison of the results, I have concluded that Linear Discriminant Analysis gave the best results (accuracy of 0.9643705463182898). 

![image](https://github.com/AHromic1/Digital-signal-processing-in-a-smartwatch/assets/115954313/7d42b622-caef-4220-a1b5-44235b0024ca)
