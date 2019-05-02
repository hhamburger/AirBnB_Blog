# AirBnB_Blog
Udacity Project "Write a Data Science Blog Post"

MOTIVATION FOR THE PROJECT

This project is apart of the second term Udacity Data Science NanoDegree program which requires to use a CRISP-DM process to communicate
answers to questions.  An AirBnB dataset was chosen to answer interesting aspects of AirBnBs in the Seattle area. This project
facilitates learning how to clean up data from different datasets by removing missing values and fixing incorrect datatype for
calculations and discovering categorical datatype issues.  It also helped facilitate learning how to write a blog and how to create a
good GitHub Repository.

LIBRARIES USED

The Jupyter Notebook File contained in this repo makes use of following libraries:

The pandas python library was used to create DataFrames and queries on those DataFrames to answer questions about an AirBnB. 

The datetime library was also imported to change dates that had string datatypes into datetime so that dates can be manipulated.

TextBlob is library imported to create sentiment values for reviews found in the reviews.csv file.  These results were used to answer
some of the questions in the blog.

Matplotlib was used to create some of the graphs used in the blog.

THE FILES INCLUDED IN THIS REPOSITORY

Seattle_Air_BnB_Blog.ipynb  =  A Jupyter Notebook of the project that shows the process of data wrangling each of the three datasets.
It also creates the statistics for the graphs and produces the graphs used in the blog.

calendar.csv - A csv file that contains data about listings for a whole calendar year including the date posted, its availability and
its price.

listings.csv - A csv file that contains listings with information about an AirBnB listing including location in Seattle, information
about the owner, description of the AirBnB and what it offers, and different prices and fees associated with the AirBnB

reviews.csv - A csv file containing reviews aobut different AirBnB listings. 

bookable_output.png , scatter.png, season.png, season_reviews.png -  All the graphs used in the blog

RESULTS OF ANALYSIS

Three questions were asked and analysis of the data was performed to answer them.

The first question asked was when is the best time to go to Seattle. The calendar dataset and reviews dataset helped to answer that by
determining prices by season from the calendar dataset and during which season is there is more negative sentiment in a review from the
reviews dataset.

Another question asked is how the cancellation policy of an AirBnB relates to whether it is Instantly bookable or not and how one should
approach the aspect of extra people.  This analysis showed that strict cancellation policies that are not bookable have higher prices
while flexible cancellation policies that are instantly bookable have the lowest prices.

The last questions determined the relationship between the review rating and the amount of people the AirBnB can accommodate.  Analysis
showed that between 3-5 people in an AirBnB gave the highest review ratings and that more than that would likely result in a lower
review rating for the owner.

ACKNOWLEDGEMENTS

Robert Chang, a data scientist from AirBnB helped explain the aspects of the project on within the Udacity Classroom.  

The three csv files come from the AirBnB page on Kaggle.com
