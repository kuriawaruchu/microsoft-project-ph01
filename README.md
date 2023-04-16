MICROSOFT MOVIES - CAN IT HAPPEN?
![image](https://user-images.githubusercontent.com/128396973/232337617-ab533a5c-f229-42c9-a6ad-cde55e34e351.png)

Overview
Microsoft wants to start creating original video content. 
This exploration incorporated various public movie datasets that contain information on films in the box office. 
They were then used to provide insight on the viability of the project for Microsoft, i.e. what the company should consider before embarking on the project. 
Some findings include the top grossing movies, movie genres and studios as well as genres that had the most movies.
Recommendations given include using more recent data (2018 to date) to provide updated information. and look into modern-day content such as social media content, live streaming to be able to compete with established studios. 

Business Problem
What are the top grossing movies? The details will guide Microsoft on movie types to emulate.
What is the performance of movies by genre - number of movies, gross income, ratings? This will inform on the genres worth investing in.
How useful is the performance of a studio in terms of gross income? Microsoft may look into engaging the studios/directors for the content creation.

The datasets used in this analysis are:
Box Office Mojo
Determining the income returns per movie over the years.
TheMovieDB
Gauging the performance of films in the box office, hence, deciding on, for instance, the most popular genres.
IMDb – an SQL database
The files of interest were imdb.title.basics.csv.gz (genre information and reviews) and imdb.title.ratings.csv.gz
Movie Data ERD
Movie Data ERD"

Deliverables
Non-Technical Presentation
GitHub Repository
Jupyter Notebook
Action Steps
Recommendation 1 - Compete with Big Studios

Using data from BokOfficeMovie.com and the-numbers.com, I was able to create a data set that produced the the profits for all studios. The process included data cleaning and calucluating total profit. Data Visualization provided below.

Lifetime Studio Profits Chart

Recommendation 2 - Create Multi-Genre Movies

Data from IMDB.com was used to create a dataframe that would be used to comparem multi and single Genre movies. The data had to be cleaned to separate and categorize each movie and genre. Data visualization can be found below.

Multi-Genre Movie Chart

Recommendation 3 - Focus on Biographies

The same data was used from Recommendation 2 to get the average rating for each genre. Please, see the data visualization below for details.

Average Rating By Genre Chart

Repository
images
awesome.gif
microsoftlogo.png
movie_data_erd.jpeg
pdf
microsoft-pres.pdf
zippedData
bom.movie_gross.csv.gz
im.db.zip
rt.movie_info.tsv.gz
rt.reviews.tsv.gz
tmdb.movies.csv.gz
tn.movie_budgets.csv.gz
student.ipynb
CONTRIBUTING.md
Instructions.md
LICENSE.md
README.md
