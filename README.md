# Amazon_Vine_Analysis
## Overview of the analysis
- In this project, I got to preform the ETL process to extract the dataset that contains some reviews of electronic products, transform this data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Also i used PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset as the goal of this project is to analyse Amazon reviews written by members of the paid Amazon Vine program.

## Results

## How many Vine reviews and non-Vine reviews were there?
- In the electronics dataset there are <b>1080</b> vine reviews and <b>49673</b> non-vine reviews. <img width="1406" alt="nonvne" src="https://user-images.githubusercontent.com/61424555/129252064-0dd92594-ebaf-4fe3-b9ee-ada5ac798647.png">
- In the electronics dataset there are <b>49673</b> non-vine reviews. <img width="1406" alt="nonvne" src="https://user-images.githubusercontent.com/61424555/129252113-df02805d-1ce8-4889-a5fe-2cae62cae284.png">


## How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Vine reviews with 5 star rating : 454 
- Non-vine reviews with 5 start rating: 23043
<img width="1406" alt="nonvne" src="https://user-images.githubusercontent.com/61424555/129252754-3192337d-626c-455f-968a-f2f44f4e29a5.png">

## What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- Percentage of the five_star reviews were vine is : 42.03% <img width="1361" alt="Screen Shot 2020-11-08 at 6 59 01 PM" src="https://user-images.githubusercontent.com/61424555/129255847-cb3d5938-ab2d-4369-8911-e90fc5a86fee.png">
- Percentage of the five_star reviews were non-vine is : 46.38% <img width="1361" alt="Screen Shot 2020-11-08 at 6 59 01 PM" src="https://user-images.githubusercontent.com/61424555/129255862-89a5eb74-79e7-49e6-a010-df9904e61424.png">

## Summary
- It appears after analyzing the data that there is a small diffrence of 4.35% between the vine reviews (42.03%) and the non-vine ones (46.38%) which represents a slight bias of them in the vine program.
- In addition to this analyse we could calculate the mean, median and mode of the dataset for the Vine and non-Vine reviews.
