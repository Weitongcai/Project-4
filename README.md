Project Title:  Yelp Data Analysis
Group Members: Mia Yang, Gina Jiaying Lu , Weitong Cai, Christina Shen
Project Description: Continue on Project 3 to detect fake reviews & predict rating
Technologies: Pick from list: Python, pandas, Web Scraping, API, SQL, HTML/CSS/JS, Flask, Big Data, Machine Learning
What We Need: All-around
What We Have: https://github.com/Weitongcai/Project-4.git
Ideal Outcome:Our analysis is to help users to use YELP efficiently and accurately

Design & Work Breakdown Structure

Part 1: Selection and Filtering (Weitong /July 24)
Based on the selected dataset Filter out  all restaurants in the USA.
Dataset source: https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset

Part 2: Cleaning (Weitong/July 26)
Import the dataset as Pandas DataFrame for future clean-up
Categorise all restaurants by cuisine type 
Delete all dataset with null category
Label restaurants above rating of 4 as “Excellent”, below rating 3 label as “OK”, label rating 3 to 4 as “Great”.
Then we populated the cleaned data into the database and saved it to local files_SQL/ELT backend
* the review.csv file is too lager, please ues the link below to access it:
* https://drive.google.com/file/d/1q0kVjGUr57b79XNxDcln6r3iWqnU5VfL/view?usp=sharing
* 

Part 3: Visualisation (Mia, Christina, Gina/July 27)

Visualize the distribution of restaurants and reviews by category .
Visualize the distribution of restaurants and reviews by rating.
Visualize top 10 negative words and positive words in each cuisine type.


Part 4 : ML MODEL  (Christina,Gina, Weitong/July 31 & Aug 2)

Predict the star rating for reviews:
SCIKIT LEARN: fit/train, and predict
Data Processing: Spark,Pandas,flask


