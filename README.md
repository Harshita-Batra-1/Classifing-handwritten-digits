# Handwritten-Digit-Recognition
This is the project of classification of handwritten digits. 
Here I have taken an input image of handwritten numbers and then I have used a machine learning algorithm (including Logistic regression, Random forest, CNN) to identify each of these numbers actually are.

At first, I have trained the classifier with the datasets of 5000 handwritten digits ranging between 0 and 9 (500 for each digit). Each digit is a 20x20 image. So my first step is to split this image into 5000 different digits. For each digit, I flatten it into a single row with 400 pixels. That is my feature set, i.e. intensity values of all pixels. It is the simplest feature set we can create. I have used first 350 samples of each digit as train_data, and next 150 samples as test_data.


Random Forest gave 96.666% accuracy

Logistic Regression gave 55.869% accuracy

Nuetral networks algo gave 
- 92.619% accuracy by simple NN
- 97.450% accuracy using NN with hidden layer too

Input Images like -
![image](https://user-images.githubusercontent.com/101546087/194817303-faedac6b-e8f8-49b4-9eec-f82033a9a817.png)

Best Accuracy by nuetral networks algorithm i.e. 97.45%

correlation heatmap -
![image](https://user-images.githubusercontent.com/101546087/194817886-6802d78d-2a06-4a0c-98c5-705be7f4e637.png)
