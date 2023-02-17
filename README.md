# Introduction

![1_ezPmZkV8VyL1Pppqa0fFhQ](https://user-images.githubusercontent.com/111365771/219646623-03b80f61-d637-4f8b-b59e-74927fdb8f28.jpeg)

For this project, I used Kaggle’s Red Wine Quality dataset to develop multiple classification models to predict whether a certain red wine is “good quality” or not. Each wine in this dataset is assigned a “quality” value between 0 and 10.11 main features which were used to predict the quality is listed below

1)Fixed acidity

2)Volatile acidity

3)Citric acid

4)Residual sugar

5)Chlorides

6)Free sulfur dioxide

7)Total sulfur dioxide

8)Density

9)pH

10)Sulfates

11)Alcohol

#Purpose

The main aim of the project is to use different machine learning models to predict the quality of wine.We compare the accuracy of each model at the final section.

# The magic

![download](https://user-images.githubusercontent.com/111365771/219647301-371336f7-9dd5-41ee-8d39-3d6c46f8c9e0.png)

oneAPI is a set of libraries and a language that makes expressing parallelism straightforward and unified. There are many different toolkits available, and one will need to select the appropriate one based on the domain. Since this is the foundation for all of the toolkits, the Intel oneAPI base toolkit is considered an add-on toolkit.
For this project i have used the **scikit-learn-intelex** to speed up my Scikit-learn application and it boosted the accuracy of  sequential model by more than 10% 

# Results
When looking at all three models side by side, the random forest LGBMClassifier appears to produce the highest level of accuracy, which is approximately 84%. The sequential model came in second with 66%, and the random forest came in third with 82%.

![download (6)](https://user-images.githubusercontent.com/111365771/219648767-44c40462-f308-422f-853f-a90d3d8c9913.png)
