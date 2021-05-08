# Analysis of Factors that affect House Price Index (HPI)

## Project Description 
The objective of the project was to analyze the relationship between various factors that impact HPI such as Weather and Disaster data for IL, FL, CA. Data cleanup was performed in Jupyter Notebok. A Dashboard was created in Tableau. FBprophet was used to forecast climate trends. A multiple linear regression was created to test if weather and disaster had an affect on HPI.
## Tools 
1. Python
   - FBprophet
   - Pandas
2. Tableau
## Steps 
### 1. Aquiring Data 
Data for Diaster data for each state was aquired through NOA. Housing Data
### 2. Cleaning Data
Data was cleaned using python pandas.
### 3. AnalysisPandas
Data was analyzed on Tableau.
### 4. Prediction
Machine learning was used to predict trends with FBprophet.

# Analysis

## Housing Data
We compared housing data to average income for each house pricepoint to see the correlation for each state.

## Illinois
![image](https://user-images.githubusercontent.com/60550835/116014784-f971d900-a604-11eb-9d77-42305ef34c12.png)
![image](https://user-images.githubusercontent.com/60550835/116014802-0f7f9980-a605-11eb-9b76-5b636cff5f71.png)

## Florida
![image](https://user-images.githubusercontent.com/60550835/116024006-524c6c00-a61b-11eb-805f-4aab139e662e.png)
![image](https://user-images.githubusercontent.com/60550835/116024025-5aa4a700-a61b-11eb-95da-5aa74e49b160.png)

## California
![image](https://user-images.githubusercontent.com/60550835/116024285-e0285700-a61b-11eb-850b-409e0c59f256.png)
![image](https://user-images.githubusercontent.com/60550835/116024296-e74f6500-a61b-11eb-8a04-e85b7f50a52d.png)

# Weather Predict
We used Fb-prophet to predict the different temperature trends for each state.

## Illinois
![image](https://user-images.githubusercontent.com/60550835/116175079-a61f8980-a6dd-11eb-94ca-9bff50190f99.png)
![image](https://user-images.githubusercontent.com/60550835/116175128-bd5e7700-a6dd-11eb-9e0c-f57cf4e31bef.png)

## Florida 
![image](https://user-images.githubusercontent.com/60550835/116175197-de26cc80-a6dd-11eb-9130-d788fd8f0f09.png)
![image](https://user-images.githubusercontent.com/60550835/116175219-e4b54400-a6dd-11eb-82ca-9f6607cd1f23.png)

## California
![image](https://user-images.githubusercontent.com/60550835/116175344-1c23f080-a6de-11eb-95e3-2e367a78721f.png)
![image](https://user-images.githubusercontent.com/60550835/116175721-de739780-a6de-11eb-84cf-93d1d6177dce.png)

# Disaster Data
We collected data on the most widely occuring diaster for each state. For Illinois we focused on Tornadoes. For Florida it was on Hurricanes. For California it was wild fires.
## Illinois
![image](https://user-images.githubusercontent.com/60550835/116434702-a4a6ac00-a818-11eb-9536-a999aaa6908d.png)
![image](https://user-images.githubusercontent.com/60550835/116434773-b5572200-a818-11eb-81cb-b089e2254799.png)

## Florida 
![image](https://user-images.githubusercontent.com/60550835/116435691-a3c24a00-a819-11eb-8e76-e4a91ec1186e.png)
![image](https://user-images.githubusercontent.com/60550835/116435742-b3da2980-a819-11eb-9879-7497c186c1de.png)

## California
![image](https://user-images.githubusercontent.com/60550835/116435815-c6546300-a819-11eb-82d8-96c7e96e2b21.png)
![image](https://user-images.githubusercontent.com/60550835/116435886-d704d900-a819-11eb-9bbc-be8ba2a85dac.png)

# HPI Predictions
Fb-prophet was used to run predictions about future HPI
## Illinois
![image](https://user-images.githubusercontent.com/60550835/116436780-bc7f2f80-a81a-11eb-83f7-66f47fb43a3e.png)
![image](https://user-images.githubusercontent.com/60550835/116436849-cdc83c00-a81a-11eb-8340-1a193184fa3a.png)

## Florida
![image](https://user-images.githubusercontent.com/60550835/116436912-dcaeee80-a81a-11eb-83d1-21b7806e6803.png)
![image](https://user-images.githubusercontent.com/60550835/116436944-e6385680-a81a-11eb-88c5-39e2a83264aa.png)

## California
![image](https://user-images.githubusercontent.com/60550835/116441116-27326a00-a81f-11eb-8d5b-a75c908c3925.png)
![image](https://user-images.githubusercontent.com/60550835/116441221-4204de80-a81f-11eb-9678-55845276412a.png)






