PySparkReviewRestaurant Project
Overview
The PySparkReviewRestaurant project focuses on analyzing and processing restaurant reviews using PySpark. The project uses the yelp_academic_dataset_review.json dataset from Yelp, containing user reviews of various businesses. The primary goal of the project is to perform data analysis and generate meaningful insights from the reviews, including sentiment analysis, rating distributions, and text processing to discover common patterns or trends.

Dataset
The dataset used is part of the Yelp Open Dataset. Specifically, we use the yelp_academic_dataset_review.json file, which contains millions of user reviews for businesses across various categories.

Each record in the dataset contains the following key attributes:

review_id: Unique ID of the review.
user_id: Unique ID of the user who wrote the review.
business_id: Unique ID of the business being reviewed.
stars: Star rating given by the user (1-5).
date: Date the review was written.
text: The full review text.
useful, funny, cool: Votes the review received for these categories.

Link data: https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset?select=yelp_academic_dataset_review.json
