# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
![Screenshot 2025-04-18 112418](https://github.com/user-attachments/assets/038c90a9-574f-4b93-afa2-8c4b31f6a24f)
![Screenshot 2025-04-18 112429](https://github.com/user-attachments/assets/0a703b02-401c-456f-b1ae-d4e3128ec565)
![Screenshot 2025-04-18 112440](https://github.com/user-attachments/assets/39c79b7e-a2c2-4284-b4bb-2d8c6ed9abf6)
![Screenshot 2025-04-18 112450](https://github.com/user-attachments/assets/f19387ba-f8c9-4f5c-818d-56de7e520ed5)
![Screenshot 2025-04-18 112501](https://github.com/user-attachments/assets/98661c76-54d7-4f27-856e-9ac1f57e1866)
![Screenshot 2025-04-18 112520](https://github.com/user-attachments/assets/4f5d8658-2246-4426-b3f6-81236b04a1bb)
![Screenshot 2025-04-18 112546](https://github.com/user-attachments/assets/6851da96-f69a-481f-b598-590bbf8b2967)


# RESULT:
       The Feature Scaling process and Feature selection process is succussfully completed.
