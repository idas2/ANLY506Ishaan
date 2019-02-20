# ANLY506Ishaan
This repository is a collection of code and charts used in the final project for ANLY 506. Each student has to choose a dataset from two options, follow the epicycles of analysis and perform a data analysis.

## Project Objectives

Each of the following steps need to be conducted for the final project.
1. Set up your questions - 20pts
2. Describe your data - 10pts
3. Explore data - use as many methods as you have learned to gain insights from data. For example, provide descriptive summary and exploratory plots, look for missing data, data variation, look for patterns (clusters). Revise your question if needed, look for additional information as needed. Provide a full explanation/description for each figure. Document your workflow and data wrangling. 40pts
4. Visualization - make sure you have proper plots, legends, color, symbols.  5pt
5. Report your findings - make sure to provide answers to your questions. Write a summary of your fundings in your report 10pts
6. Use of R and RMarkdown - 10pts [proper syntax, documentation, output] Use code chunks and also in-line code, header, fonts, title etc
7. Upload your code files to your github project and add a direct link in your report. 5 pts

## Prerequisites

The project is created using R and follows the epicycles of analysis from Roger Peng's book "The Art of Data Science". So installing R and reading the book are the most important prerequisites.

## Data Description

- The name of the dataset is bikeVendors
- You can download the dataset from the folder data
- The data set has 5 main columns: bike model, category1, category2, price and frame type
- The data also contains obervations for different bike vendors. The observations for each bike vendor add up to 1 indicating that they are a ratio of revenue or profit gained from each bike. I will assume they are revenue contributions from each bike.
- There are a total of 97 observations

## Analysis

- The primary question of interest is Which bikes lead to the highest revenue contribution?
- We will use ggplot2 to create charts and glean our data.
- We will then use K-means and Heirarchical clustering to cluster our data.
- Based on the clusters we will try to identify the bikes that provide the highest revenue contribution.