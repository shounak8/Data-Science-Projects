Greetings !!

I am Shounak Deshpande (Python Engineer, Web Developer and AIML/Data Science practitioner, Ex-HR).

This project is about building a recommendation system of Electronics and Modcloth items.

2 Datasets are given giving sales details of Electronics and Modlcoth items.


Full details are mentioned in the "Capgemini Recommendation System Project.ipynb" notebook.
Please open the .ipynb file via Jupyter or Google Colab or any other tool which supports the .ipynb file.

If you do not have the tool which opens .ipynb file, you may refer to the .html file (please open via browser).

A Powerpoint Presentation is also included.

These files are included in the .zip folder.





Brief Step by Step Walkthrough of the project is as below:

Step 1 : Importing Libraries, loading data to form Dataframes & Preliminary Data Exploration

Step 2 : Data Cleaning (removing duplicate values and dealing with missing values)

Step 3 : Feature Engineering & Exploratory Data Analysis - New features are added to the dataframe which will be useful to us in Data Analysis. 
	 Given data is analysed and meaningful conclusions are drawn which we use to build our recommendation system.

Step 4 : Removing Bias - We remove items which have sold less than 50 units. This is to compensate for probables cases where the producer has bought his own items and rated it highly &
	 cases where the loyal customers have bought the same product time and again and have rated it high.

Step 5 : We build recommendation system based on Ratings, Units Sold & Market basket analysis (Apriori - Association Rules)

	 First Parameter Considered - Ratings
	 We build recommendation system based on Ratings of the items. 
	 We recommend items as well as brands based on rating.
	 Recommendation is done for both: the entire time-period i.e. from 1999 to 2019 as well as considering the 
					  latest trend i.e. for past 2 years (2017 to 2019)

	 Second Parameter Considered - Number of Units Sold
	 We build recommendation system based on Number of Units Sold. The higher the number of units sold, the more popular the item is.
	 We recommend items as well as brands based on Units Sold.
	 Recommendation is done for both: the entire time-period i.e. from 1999 to 2019 as well as considering the 
					  latest trend i.e. for past 2 years (2017 to 2019)


	 Third Parameter Considered - Market Basket Analysis (Apriori - Association Rules)
	 We build recommendation system based on Apriori Algorithm.
	 We consider only those users who have bought more than 2 items over the course of time.
	 We try to associate these items with each other to find the likelihood the user will buy "Item B" based on the user selecting "Item A".
	 Here, We recommend items and categories.




If you like my work or wish to collaborate over any project, please let me know at shounak.python@gmail.com