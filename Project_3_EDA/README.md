# <center> Skillfactory Project 3: Exploratory Data Analysis

## Table of Contents  
[1. Project Description](https://github.com/KarpovGm/Booking_reviews_Project_3/blob/main/README.md#project-description)  
[2. What Case Are We Solving?](https://github.com/KarpovGm/Booking_reviews_Project_3/blob/main/README.md#what-case-are-we-solving)  
[3. Brief Data Overview](https://github.com/KarpovGm/Booking_reviews_Project_3/blob/main/README.md#brief-data-overview)  
[4. Project Stages](https://github.com/KarpovGm/Booking_reviews_Project_3/blob/main/README.md#project-stages)  
[5. Results](https://github.com/KarpovGm/Booking_reviews_Project_3/blob/main/README.md#results)    
[6. Conclusions](https://github.com/KarpovGm/Booking_reviews_Project_3/blob/main/README.md#conclusions) 

### Project Description    
Imagine you are a data scientist at Booking.com. One of the company's problems is dishonest hotels that artificially boost their ratings. One way to detect such hotels is to build a model that predicts hotel ratings. If the model’s predictions significantly differ from the actual results, it might indicate dishonest behavior, and such hotels should be investigated.

Your task is to create such a model.

:arrow_up:[back to top](https://github.com/KarpovGm/Booking_reviews_Project_3/blob/main/README.md#table-of-contents)


### What Case Are We Solving?    
The aim of this project is to clean data, design new features, and completely prepare the data for subsequent model training.

**What we practice**     
    - Solving Data Science cases
    - Reinforcing the material covered in the course
    - Python
    - EDA (Exploratory Data Analysis)


### Brief Data Overview
#### Hotel-related features
1. hotel_name - full hotel name;
2. hotel_address - address: street, post code, city, country;
3. lat - hotel latitude coordinate;
4. lng - hotel longitude coordinate;
5. average_score - average hotel rating;
6. total_number_of_reviews - total number of hotel reviews;
7. additional_number_of_scoring - number of hotel scores without review.

#### Reviewer-related features
1. reviewer_nationality - reviewer's nationality;
2. total_number_of_reviews_reviewer_has_given - total number of reviews given by the reviewer;
3. tags - tags describing the stay at the hotel.

#### Review-related features
1. review_date - date of review;
2. days_since_review - difference in the number of days between review date and scrape date;
3. negative_review - text of negative review;
4. review_total_negative_word_counts - count of words in negative review;
5. positive_review - text of positive review;
6. review_total_positive_word_counts - count of words in positive review.

:arrow_up:[back to top](https://github.com/KarpovGm/Booking_reviews_Project_3/blob/main/README.md#table-of-contents)


### Project Stages  
The project is divided into five stages:
    1. Data loading and preliminary analysis
    2. EDA
        2.1 General analysis
        2.2 Finding correlations (not included in the notebook)
        2.3 Feature creation and transformation
            2.3.1 Extracting information from text features
            2.3.2 Working with dates
            2.3.3 Handling missing data
        2.4 Analyzing feature contribution to the target variable
        2.5 Analyzing multicollinearity and feature selection
    3. Model training
    4. Submitting the model

All these stages are initially worked on a local machine and then uploaded to Kaggle.

:arrow_up:[back to top](https://github.com/KarpovGm/Booking_reviews_Project_3/blob/main/README.md#table-of-contents)


### Results:  
This project required a lot of effort and faced significant challenges. The main difficulty was the absence of any clear guidelines on what and how to do things. The project required a personal approach to solving the task, which was to achieve the best MAPE (mean-absolute-percentage-error) score. I managed to achieve a MAPE of 12.115, which is quite a good result, though there is room for improvement. In conclusion, I would like to say that during the project, through many errors, I gained a lot of knowledge and overall am satisfied with my solution.

:arrow_up:[back to top](https://github.com/KarpovGm/Booking_reviews_Project_3/blob/main/README.md#table-of-contents)

