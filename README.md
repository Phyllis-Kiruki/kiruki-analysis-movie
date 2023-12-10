## **Microsoft Studio Movie Data Analysis**

## **Overview**
This project analyses two datasets to uncover patterns and trends that contribute to a movie's success. Primary focus revolves around two key findings: the influence of movie genres on profitability and the impact of film length on financial success.

## **Business Problem**
Microsoft company wants to open a movie studio. Inorder to be successful they would require data driven decisions in their movie production process in order to create popular and more importantly, profitable movies.

## **Question for Analysis**
-. Which movie genres demonstrate the highest average profitability?
-. What is the ideal length for a movie?

# **Datasets**
 This project analyses datasets encompassing a wide range of movies spanning various genres, release periods, and production scales. These datasets are rich in both historical and contemporary film information, providing a robust foundation for our analysis.

 **BomMovie Dataset**

BomMovie dataset is comprised of records on 3387 movies and includes 5 columns. column of interest would be foreign gross.

**IMDB Dataset**

IMDB dataset is comprised of multiple tables containing various information about movies. The two tables of interest are: `movie_basics` and `movie_ratings`.

## Data Preparation
Unnecessary columns are dropped in the datasets then the datasets are merged to be one large dataset named Database where analysis is performed.

The Database is filtered where average rating of `7`, foreign gross of `27.9` million and genres are split to its own is used to find most profitable genre.

For ideal lenght average rating of `7` and runtime minutes of less or equal to `300` are filtered and analyzed to find the movie length liked by the audience.

## **Conclusion**
`Genre`

Adventure genre is the most profitable.

`Movie Length`
Movie length of 90 minutes is liked by audience.

## **Recommendation**

It is recommended for Microsoft movie studio to produce more adventure genre films.

It is recommended for microsoft movie studio to produce films of 90 minutes long.