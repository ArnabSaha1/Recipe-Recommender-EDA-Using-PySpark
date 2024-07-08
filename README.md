# Recipe Recommender Assignment EDA Using PySpark

![image](https://github.com/ArnabSaha1/Recipe-Recommender-EDA-Using-PySpark/assets/170148135/4d7657d6-a4cc-400f-9df1-efe6b4e6e232)

## Problem Statement:
Food.com is afood recipe website where an user posts the food recipes and other users rate and comment on it. As an ML engineer working at food.com. Your job is to design a recommender system to recommend recipes 
to users based on their choice and the current recipe they are looking at. The recommendation engine is a way to increase the website's user engagement. If a user is shown relevant recipes, they are more likely to spend more time on your site reading about recipes. Higher user engagement will likely result in more business opportunities like collaborations, promotions, etc.–The performance of a recommendation engine will significantly impact the revenue your recipe site can generate.

## Objective:
Designing a recommender from scratch is a time-consuming task.–In this assignment, we have used PySpark for the Data Analysis Purpose.–Here we explored the raw data and created several features thatcan be used to build the recommender engine.

## Datasets
The data consists of two files. The first file is the Raw_recipes.csv file. It contains all the recipe-related information. Each row in this file describes a recipe.–The second file we will be using is the RAW_interactions.csv. Each row in this data file is one user reviewing one recipe.–One user can review more than one recipe, and each recipe can be reviewed by more than one user, so there is a many-to-many relationship between users and recipes, but the combination of user_id and reviewer_id in each row will be unique.

## Steps:
In this assignment we have utilised PySpark and Google Colab for performing the big data analysis. You can also use AWS EMR, one master node with m4.xlarge and one cluster node with m4.large configuration will give you sufficient processing power to work with this data. Following are steps that followed:
- Part 1: Recipe Based Feature Extraction & EDA
    - Task 01: Reading the first data file.
    - Task 02: Extract individual features from the nutrition column.
    - Task 03: Standardize the nutrition values.
    - Task 04: Convert the tags column from a string to an array of strings.
    - Task 05: Read the second data file.
    - Task 06: Create time-based features.
    - Task 07: Processing Numerical Columns and Visualising.
- Part 2: User Based Feature Extraction & EDA
    - Task 08: Create user-level features.
    - Task 09: Create tag-level features and perform EDA.
 ## Summary:
After performing the feature extraction and exploratory data analysis on the raw data, we comes up with several features that can be used to build the recipe recommendation engine for the food recipe website Food.com.– And using this recommendation engine will not only help in increasing the website's user engagement, more business opportunities like collaborations, promotions, etc. but will also help significantly impact the revenue growth of the company.
