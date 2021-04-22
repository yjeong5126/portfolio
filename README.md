# YohanJeong_Portfolio
This Portfolio contains data-related projects.  

## [Project 1: Scraping Box Office Info Using Scrapy](https://github.com/yjeong5126/scraping_boxofficemojo)

[Medium Post](https://medium.com/analytics-vidhya/scraping-box-office-info-with-scrapy-f23f1f2d684f)

- Scraped the *Boxofficemojo* website using Scrapy in Python. 
- Checked all the movies released in the US during certain periods of time and extracted useful information about the individual movies. 
- For each movie, *Domestic Revenues, Worldwide Revenues, Distributor, Opening, Budget, MPAA, Genres, and In Release* are scraped.

## [Project 2: Analysis of Movies and their Trailer Release Dates](https://github.com/yjeong5126/movietrailer_releasedate) 

[Medium Post](https://medium.com/@yjeong5126/analysis-of-movie-trailer-release-date-3c6e30681aea)

- Scraped the *Boxofficemojo* and *Traileraddict* websites to get movie information.
- Explored movie features such as budget, distributors, MPAA, and genres.
- Examined whether the variation in the promotion period is related to such features. 

![](/images/budget_promotiondays.PNG)

## [Project 3: Predicting Housing Prices using Cross Validation and Grid Search in Regression Models](https://github.com/yjeong5126/housing_prices)

[Medium Post](https://medium.com/@yjeong5126/predicting-housing-prices-in-melbourne-e3d5f49abf20)

- Analyze the factors related to housing prices in Melbourne and performed the predictions for the housing prices using several machine learning techniques. 
- Employed *Linear Regression, Ridge Regression, K-Nearest Neighbors, and Decision Tree*. 
- Found the optimal values for hyper parameters in each model using the methods of the *Cross Validation* and *Grid Search* techniques.
- Compared the results to find the best machine learning model to predict the housing prices in Melbourne. 

![](/images/cross_val_summary_graph.PNG)

## [Project 4: Creating a Database and Practicing SQL Queries](https://github.com/yjeong5126/sql_sample_sales_data)
[Medium Post 1](https://medium.com/swlh/creating-a-database-converting-a-spreadsheet-to-a-relational-database-part-1-2a9a228bf77a)
[Medium Post 2](https://yjeong5126.medium.com/creating-a-database-converting-a-spreadsheet-to-a-relational-database-part-2-faf4fc83bae5)

- Converted a data in one spreadsheet to a relational database for SQL.
- Performed several SQL queries using the database.

## [Project 5: The Analysis for Glassdoor Job Postings](https://github.com/yjeong5126/glassdoor_data_analyst)

- Scraped over 3000 job postings for 'Data Analyst' from the Glassdoor website using the *Selenium* library in the Python
- Cleaned the scraped data using the Python.
- Converted the data to the format for the Relational Database to store it in the SQL format.
- Visualized the data using *Tableau*, showing the salary distributions by state, city, sector, and skills.

![](/images/tableau_captured.PNG)

## [Project 6: Cohort Analysis](https://github.com/yjeong5126/eCommerce-Analysis/blob/master/cohort_analysis/e_commerce_cohort_analysis.ipynb)

In this project, I implement the cohort analysis using eCommerce data from UIC machine learning repository. In the code, I show how to create the matrix for cohort analysis from the raw ecommerce data. 

## [Project 7: Making a Content-based Movie Recommender](https://github.com/yjeong5126/movie_recommender)

Among the several recommendation models, I build a **content-based** recommendation engine in this practice. I used a movie data set from the **MovieLens**, which has 9742 movies. The first step is to quantify the movie features using the **Term Frequency and Inverse Document Frequency (tf-idf)**, and the next step is to calculate the similarities between movies using the **cosine similarity**. Furthermore, I add the '**Did you mean...?**' function to the recommender in order to make the searching process easier.

[Medium Post](https://yjeong5126.medium.com/creating-content-based-movie-recommender-with-python-7f7d1b739c63)

## [Project 8: Making an Item-based Collaborative Filtering](https://github.com/yjeong5126/movie_recommender)

Among the several recommendation models, I build an **item-based** collaborative filtering for movie recommendation. I used a movie data set from the **MovieLens**. In order to predict a rating for a movie by a selected user, the first step is to find similar movies to the movie using the **cosine similarity**. The next step is to calculate the weighted average of ratings for the similar movies by the user. Then, the average can be the predicted rating for the movie by the selected user. Applyting this algorithm, I built a movie recommendation for the movie dataset.

[Medium Post](https://yjeong5126.medium.com/item-based-collaborative-filtering-in-python-91f747200fab)
