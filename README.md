# MSCI-436-Final-Project

## Introduction
Our end user is a landscaping company seeking to launch an advertising campaign in a specific neighborhood in Ames, Iowa.

Our objective for this campaign is to analyze various characteristics of houses in that neighborhood in order to anticipate the impact or potential increase in their value.

We will examine the correlations between specific house characteristics and their corresponding prices. This analysis will help us determine whether services offered by our landscaping company, such as adding a fireplace or improving basement finishing, have the potential to enhance the value of a house.

## Data
For this project we used the ["House Prices"](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview) dataset found on Kaggle. We utilized the characteristics of this dataset to develop a regression model that utilized these features as inputs to make predictions about the Sale Price. To assess the accuracy of the model, we divided the data into an 80/20 split, allowing us to train the data and test its performance.

## The User Interface 
We designed our user interface with the end user as the focal point. As we developed this regression model for the landscaping company, our primary goal was to create a user-friendly interface that the company could utilize as an effective marketing tool to potential customers. (The UI is intended to be viewed in streamlit's wide mode.)

<img width="2484" alt="Screenshot 2023-07-13 at 3 17 30 PM" src="https://github.com/SarankanT/MSCI-436-Final-Project/assets/60015755/0d29470a-0a30-4d23-b611-c6e093289a7b">

<img width="2474" alt="Screenshot 2023-07-13 at 3 17 48 PM" src="https://github.com/SarankanT/MSCI-436-Final-Project/assets/60015755/b1489d03-6820-4468-8753-6a5b6b9cbc8b">

![39E0126A-F24A-4329-8180-479EECBF874F_1_201_a](https://github.com/SarankanT/MSCI-436-Final-Project/assets/60015755/c71667a4-411a-4ca3-a4c6-5b50ed548174)

<img width="2489" alt="Screenshot 2023-07-13 at 3 18 38 PM" src="https://github.com/SarankanT/MSCI-436-Final-Project/assets/60015755/b16e92ca-0c3d-472a-8d73-529f791ee1b2">

## Code Format 
Section 1: Introduction 

Section 2: Install & Import Packages
  - Install streamlit and localtunnel
  - Import Packages
    
Section 3: Load Data (train.csv data)

Section 4: Clean Data 
  - Clean train data (remove null values, etc.)
  - Manipulate the dataframe (Rename columns, account for inflation rate)

Section 5: Plotting the correlations of Features vs. Sale Price
  - Plot the correlations to visualize relevent features
  - Clean data by changing datatypes and removing excess columns

Section 6: Split Data

Section 7: Create and error test the Linear Regression Model
  - Linear Regression Model
  - Calculating the MSE and R^2 Values

Section 8: Streamlit Application
  - Writing the streamlit file
  - Run the app and keep logs
