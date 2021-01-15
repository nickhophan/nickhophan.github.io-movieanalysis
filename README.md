##Movie-Streaming-Platform-Analysis
#INTRODUCTION:
Movie streaming platform industry currently becomes more popular because the increasing number of customers who would like to spend time at home to enjoy a show instead of going to the cinema or spending a long time waiting for a show time on channel. It completely changes the hobby of watchers because now people can not just only save more money but being able to enjoy more shows at any time and anywhere. For the team project, we are fortunate to get to know the data source from Kaggle (https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney) with the data provided by four famous platforms in America such as Netflix, Amazon prime, Hulu and Disney. The data set helps my team to explore many interesting aspects of movie streaming platform. We believe these findings are very helpful, (1) it can help the platform companies find out the potential limitations (for example: age limitation or inequality in genres) to improve the platform better, (2) it provided statistic data about the movie industry throughout years, which people may have less knowledge about it before, (3) this will help company to have a good prediction model, which will detect the show efficiently then recommend it for customers as accurately as possible, (4) this will help the business realizes the quality of movies that they are providing for customers to distribute the number of movies on platform appropriately.
This dataset consists of several records of movies and each of the platform they belong to. The four platforms consist of Netflix, Hulu, Prime and Disney. Each of these streaming platforms have their own column respectively and contain 0s and 1s implying if a movie is available to be viewed on them. For example, if a movie record ‘Inception’ has a 1 1 under Netflix column, then it means that ‘Inception’ is available to be watched on Netflix. Likewise, if ‘Inception’ is 0 under Hulu, it implies that the movie is not available to be watched on Hulu. 
Other columns in the dataset include Year, Age, IMDb ratings, Directors, Genre, Language and Runtime.
Here is a brief description of each column of the dataset:
1.	ID: Unique ID of each movie record
2.	Title: The name of the movie record
3.	Year: Release year of the movie
4.	Age: Target age range for each movie
5.	IMDb: rating of a movie from a scale of 1.0 to 10.0
6.	Rotten Tomatoes: rating of a movie from 1% to 100%
7.	Netflix: states whether the movie is available on Netflix
8.	Hulu: states whether the movie is available on Hulu
9.	Prime: states whether the movie is available on Prime
10.	Disney+: states whether the movie is available on Disney
11.	Directors: Name of the director(s) of each of the movie
12.	Genre: Type of movie
13.	Country: origin of the movie
14.	Language: Language of the origin
15.	Runtime: duration of the movie

 
#ANALYSIS:
The purpose to this analysis is because we want to answer the questions we have doubts at the beginning.

I.	Explanatory Data Analysis:

1.	What are top rating movies?
2.	Is there difference in the evaluation of movies from different genres on Netflix? 
3.	Ratio of international movies or (movies without English language) within each platform. This is done to understand which platform caters most to international audience.
4.	Whether the platforms have consideration to teenager customers?
5.	What are the most popular genres of American movies on different platforms? How the scores of genres are different?

II.	Method:

1.	Is there difference in the number of quality movies of 4 platforms?
2.	The correlation between the runtime of a show and its independent variables.
