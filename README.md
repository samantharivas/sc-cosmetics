# SC Cosmetics Insights with AWS
This repository contains the code for a comphrehensive project that utilizes AWS to store and transform data to build optimized classification models. The objective is to increase customers propensity to purchase by analyzing cosmetic product shopping habits and integrating educational tools that dissuade customers from purchasing products with harmful chemical ingredients. 

## Contributors 
Claire Bentzen and Samantha Rivas

## Deployment Process
1. Clone this repository to your local machine:
   git clone https://github.com/clairebentzen/sc-cosmetics.git

2. Run SC-Cosmetics.ipynb to copy S3 buckets and make the necessary data transformations.

## Abstract
People often go unaware that their cosmetic products contain potentially harmful chemicals and ingredients. SC Cosmetics provides a solution to help consumers identify harmful products and aims to increase customer’s propensity to purchase clean cosmetics. 

## Problem Statement
The state of California requires the manufacturers of cosmetic products to report any products that contain cancer-causing or potentially hazardous ingredients to the California Safe Cosmetics Program (CSCP). SC Cosmetics is an app that allows users to search or scan products to determine if it is free from potentially harmful ingredients. Additionally, there are filter options for the user to get recommendations and be introduced to new cosmetic products based on their skin type and preferences.

SC Cosmetics allows users to make purchases through links provided in the app, making clean products accessible. Not many people are taking advantage of this feature and our company aims to identify marketing and recommendation tactics that increase the number of people who place orders through the app. 

## Goals
- Develop a recommendation system within the SC Cosmetic app to help users identify cosmetic products free from potentially harmful ingredients.
- Create a skin quiz feature integrated into the app to provide personalized skincare product recommendations based on users’ skin type, concerns, and preferences. 
- Enhance transparency by providing comprehensive information about chemicals present in cosmetic products, including a product ranking, and educating consumers about their potential effects on skin health.
- Improve accessibility by allowing consumers to purchase recommended skin care products via the SC Cosmetic app, facilitating a seamless shopping experience for users. 
- Improve the accuracy of product recommendations by analyzing user interaction on cosmetic products and integrating consumer propensity to purchase data. 

## Non-Goals
- Providing medical advice or diagnosis based on cosmetic ingredients in products. 
- Directly manufacturing cosmetic products sold through the SC Cosmetic app. 
Analyzing customer behavior beyond the scope of cosmetic product preference and purchases. 

## Overview
The repository consists of the following components:
- Raw data
- Copying public S3 buckets to your private bucket
- Data transformations and manipulation
- Creating Athena database
- SQL queries for table creation and joins
- Exploratory data analysis
- Data visualizations
- Modeling with Amazon Experiments
- Modeling with autogluon

## Technologies Used 
- AWS S3 Buckets
- Python via AWS SageMaker Studio
- AWS Athena
- Git
- SQL

## Methods Used 
- EDA
- Data transformation
- Data visualization (seaborn and matplotlib)
- Data modeling

## References
Awan, A. A. (n.d.). Cosmetics Datasets. Kaggle. Retrieved April 5, 2024, from https://www.kaggle.com/datasets/kingabzpro/cosmetics-datasets?resource=download

Chemicals in Cosmetics. (n.d.). Data.gov. Retrieved April 5, 2024, from https://catalog.data.gov/dataset/chemicals-in-cosmetics-8c29f

P, B. (n.d.). Customer propensity to purchase dataset. Kaggle. Retrieved April 5, 2024, from https://www.kaggle.com/datasets/benpowis/customer-propensity-to-purchase-data
