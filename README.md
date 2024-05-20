# IMDb Dashboard & Analysis
## Mockup



![alt text](https://github.com/youseftaz5/IMDb-Dashboard/blob/master/MookUP/IMDb-MookUP.jpg?=raw=true)


<<<<<<< HEAD
=======
![alt text](https://github.com/youseftaz5/IMDb-Dashboard/blob/master/MookUP/IMDb-MookUP.jpg?=raw=true)
>>>>>>> origin/master

## Mindest

Before I getting start to preform analysis, creation of Dashboard. I have some questions I wanted to answer it:



1. How many Directors create movies in the list of 250 on movies ?

2. Who's the writer who's written more than one movie ?

3. Is there any movie where the writer himself is also the director ?

4. how much does every movie spent (budget) and how much the movie makes (box office) ?

5. what is the decade and year that was the peek of produced movies ?

5. some measures 

    1. Min Budget

    2. Max Budget

    3. AVG. Budget

    4. Ranking

    5. Total of Casts

    6. Count of Genre



### Data source: 



After those questions, I searched for the dataset that would be suitable for my analysis and answering my  questions.



### Data Preprocessing 



- Check on Duplication, Nulls, Etc. 

- I Created a derived column based on the year as (decade) column.

- Spliting the Directors because for each movie maybe there is more than one director 

- Create a new table and assign an ID for each columns, such as [Genre, Director, Movie, Writer, Cast]

- Modify the Data modeling 

- Modify the data types for columns







## Data Analysis & Creation Dashboard

### Overview



- Cards

    * Highest Budget

    * Lowest Budget

    * Average Budget

    * Min Rating 

    * Max Rating

    * Count of Genre

    * Count Cast

- Line Chart

    * Total Movies/per

      * Including (Highest/Lowest) movie produced over all year

      * Including (Avg.movie)

    * Total movies per decade



- Clusterd Column Chart

    * Genre of Movies



- Matrix

    * Director: Explain how much Director, Directed Movies

    * Writer  : Explain how much Writer, Wrote Movies

- 100% Stacked Bar Chart

    * Box Office Vs Budget: How much the movie make (revenue/lose) for each movie



- Filter

    * Filter By 

       * Certificate

       * Genre

       * Director name

       * Writer name

       * Cast name

       * Budget

       * Box office

       * Years

       * Decades

       * Rank

       * Run-Time

       * Movie name





## Links



1-[IMDb Brand Guide Lines](https://brand.imdb.com/imdb)



2-[Data Source](https://www.kaggle.com/datasets/rajugc/imdb-top-250-movies-dataset)

