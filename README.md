
# Google Playstore Exploratory Data Analysis

![1657557](https://user-images.githubusercontent.com/121177364/213858410-0fefa3f6-4aed-46cb-b9cb-838a98340f2e.jpg)

The Google Play Store is a digital marketplace for mobile apps on the Android operating system. These apps now significantly influence how we live our lives. The goal of this project is to provide information that will assist developers better understand client needs and, in turn, help the product become more well-known. This includes analyzing the relationship between app ratings and download numbers, identifying the most popular app categories, or exploring the sentiment of app reviews. The project also includes visualizations to help communicate the findings and insights.

# Analysis

The analysis will include the following steps:

    1. Importing Libraries
    2. Reading Data
    3. Understanding the Data
    4. Data cleaning and preprocessing
    5. Data Visualization to communicate the results
    6. Conclusion

#  Data

Two data sets are used in this project which includes the following information:

Play store data:

    1. App - Name of the Application
    2. Category - Category of the Application
    3. Rating - Rating given to the Application
    4. Reviews - No of reviews given to the Application
    5. Size - Size of the Application
    6. Installs - No of downloads of the Application
    7. Type - Free or Paid
    8. Price - Price of the Application if it is paid
    9. Content Rating - It is Age appropriate or Not
    10. Genres - Type of Genre the Application belongs to
    11. Last Updated - When the last time the Application is Updated
    12. Current Ver - Current version of the Application
    13. Android Version - Minimum Android version required to run the Application

User reviews data:

    1. App - the name of the app the review is for
    2. Translated_Review - the text of the review (translated to English)
    3. Sentiment - the sentiment expressed in the review (positive, negative, or neutral)
    4. Sentiment_Polarity - a numerical score indicating the sentiment polarity (ranging from -1 to 1)
    5. Sentiment_Subjectivity - a numerical score indicating the sentiment subjectivity (ranging from 0 to 1)

# Requirements

To run this project, you will need to have the following packages installed:

    1. Python - Programming Language
    2. Numpy - Scientific computing library
    3. Pandas - Data manipulation library
    4. Matplotlib - Data visualization library
    5. Seaborn - Data visualization library

# Usage

    * Clone the repository
    * Run the jupyter notebook google_playstore_eda.ipynb

# Conclusion

These are the general conclusions that are drawn from this EDA:

        1. Best gaming app based on rating is Monster Ride Pro\n",
        2. Best Art and Design app based on rating is Spring flowers theme couleurs d t space\n",
        3. Apps which have maximum installs are mostly free
        4. Total No. of Free apps are 8719 & Paid apps are 647
        5. App with least rating is DS Creator 2.0 is of Category ‘Tools’
        6. Apps of Category ‘Weather’ has maximum reviews
        7. Best Food and drink app based on rating is Bar B-Q Rib House
        8. App which generated the highest revenue is Minecraft
        9. Average no. of words used in Translated reviews is 18
        10. Most of user sentiments are Positive
        11. Game Category has the highest sentiment polarity rate.
        12. Maximum installed apps are Subway surfers,Facebook,Messenger & Google Drive
        13. Category with has max no. of apps with 4+ rating is ‘Family’
        14. Most expensive app on Play store is “I’m Rich” priced at 400$
        15. 1208 apps are famous among teens out of 10841 apps
        16. Highest revenue generated app belongs to Category ‘Family’
        17. Most of the apps has got the rating between 3.5 to 5
        18. Maximum no. of installations belongs to Category ‘Communication’ and ‘Social Media’
        19. Most of the apps available on play store belongs to Category ‘Family’ i.e, 20.3%
        20. Application reviews and installs are highly correlated i.e, 0.64
        21. 48 apps are Google listed and their average rating is 4.3
        22. Genre ‘Action’ has highest - 358 Gaming applications
        23. Maximum no. of applications got updated in year 2018
        24. Out of all Categories, ‘Game’ has got the most positive sentiments

![pngfind com-google-play-logo-png-488760](https://user-images.githubusercontent.com/121177364/213854305-652fd3a3-84e6-40cd-a763-9ec1c97c951b.png)
