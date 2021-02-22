# Spark-Projects
Spark Projects
# [Project 2: Moive Recommendation](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6218310713581346/2651552686218198/8364127136607238/latest.html)
In this notebook, I will use an Alternating Least Squares (ALS) algorithm with Spark APIs to predict the ratings for the movies in MovieLens small dataset

![](https://github.com/lindaray1220/Spark-Projects/blob/main/images/DSCF9048.JPG)


# [Project 3: Pets users: Youtube comments analysis](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6218310713581346/4010779937904117/8364127136607238/latest.html)
In this notebook, I have a dataset [https://drive.google.com/file/d/1o3DsS3jN_t2Mw3TsV0i7ySRmh9kyYi1a/view?usp=sharing] of user comments for youtube videos related to animals or pets. I will attempt to
(1) identify cat or dog owners based on these comments,
(2) find out the topics important to them, and then
(3) identify video creators with the most viewers that are cat or dog owners.

The dataset provided for this coding test are comments for videos related to animals and/or pets. The dataset is 240MB compressed; please download the file using this google drive link: https://drive.google.com/file/d/1o3DsS3jN_t2Mw3TsV0i7ySRmh9kyYi1a/view?usp=sharing

The dataset file is comma separated, with a header line defining the field names, listed here: ● creator_name. Name of the YouTube channel creator. ● userid. Integer identifier for the users commenting on the YouTube channels. ● comment. Text of the comments made by the users.

I used PySpark (version 2.2) to analyze the data in 6 steps as below:
STEP 0: Data Exploration and Cleaning.
Step 1: Identify Cat And Dog Owners Find the users who are cat and/or dog owners.
Step 2: Build And Evaluate Classifiers Build classifiers for the cat and dog owners and measure the performance of the classifiers.
Step 3: Classify All The Users Apply the cat/dog classifiers to all the users in the dataset. Estimate the fraction of all users who are cat/dog owners.
Step 4: Extract Insights About Cat And Dog Owners Find topics important to cat and dog owners.
Step 5: Identify Creators With Cat And Dog Owners In The Audience Find creators with the most cat and/or dog owners. Find creators with the highest statistically significant percentages of cat and/or dog owners.
