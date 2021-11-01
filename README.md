# About This Project
This project was created to use the basics of extracting, transforming, and loading a data set from csvs and json files to a SQL database. I did this by taking data from the wikipedia api about all the movie pages they had in a single json file. Then we combined that with curated data from kaggle and movie ratings from MovieLens. I cannot include all of the ratings data from those raw data files in this repository due to the upload limit of Github being only 100 MB per file. The raw ratings.csv is nearly 700 MB in size and therefore is far over the actual upload limit. I apologize for being unable to provide you with the direct data in repo but if you wish to try these files yourself please go ahead and download the raw files at Kaggle using [this direct link to the zip file I used.](https://www.kaggle.com/rounakbanik/the-movies-dataset/download)

# Screenshots 

![movie counts](/Resources/movies_count.png)

Total movies uploaded from the cleaned data set to the PGSql database used

![ratings count](/Resources/ratings_count.png)

And this is the staggering number of rows uploaded to database based on the ratings csv used in this project. As you can see due to the huge amount of rows, over 26 million, I was not joking about the size of the original file.
