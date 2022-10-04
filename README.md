# App-Rating-prediction

Objective: App ratings are always a good indicator of how good is the app. Google wants to know which apps are likely to have good ratings as these apps will be boosted for visibility. The objective of this project is to build a model to predict which apps will have high ratings.

I had data of existing apps with more information about it such as :

App: Application name

Category: Category to which the app belongs

Rating: Overall user rating of the app

Reviews: Number of user reviews for the app

Size: Size of the app

Installs: Number of user downloads/installs for the app

Type: Paid or Free

Price: Price of the app

Content Rating: Age group the app is targeted at - Children / Mature 21+ / Adult

Genres: An app can belong to multiple genres (apart from its main category). For example, a musical family game will belong to Music, Game, Family genres.

Last Updated: Date when the app was last updated on Play Store

Current Ver: Current version of the app available on Play Store

Android Ver: Minimum required Android version

# Steps performed in the analysis

Importing libraries: Pandas, numpy, matplotlib.pyplot, Seaborn

Importing Data: from csv

Cleaning Data : treat null values, object dtype to numeric datatype, data conversion for MB to KB, remove unnecessary symbols

Sanity Checks

Outlier treatment

Exploratory Data Analysis: Univariate analysis, Bivariate analysis

Data preprocessing: Apply log transformation to reduce the skew, convert cat columns to dummy columns (1,0)

Machine Learning using Linear Regression: Model building, Training the model, Predicting, Checking accuracy of the model, model improvement suggestions

# Data Insights:

1. Maximum apps belong to Family Category and then Game Category

2. Frequency of rating is distributed towards high rating

3. Frequency of size is distributed towards small size

4. Rating seem to increase with the reviews

5. Rating seem to increase with the Size

6. A correlation between Rating and Installs is not observed

7. Rating does not seem to increase that much with the Price

8. Content rating for Adults 18+ are liked better

9. Events,Parenting,Art and Design genre have better ratings

10. Paid apps have slightly better rating

11. I found that the R2 value was not very ideal in terms of a good prediction criteria.

Something that could help me improve in this project would be increasing the model complexity.

Instead of linear model, I can try more advanced, machine learning models like a tree model or a neural network.

