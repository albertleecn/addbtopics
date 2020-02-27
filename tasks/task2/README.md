# Task

## Description of Task
Task: Design a schema for movies, and import all data from movies.csv, and The Requirements are as follows: <bt/>
1. Data File is in tasks/task2: Movies Data File Structure (movies.csv)
2. retrieve the number of movies in each genre
3. reverse engineer the new schema

## Specification of movies.csv
Movies Data File Structure (movies.csv)
---------------------------------------

Movie information is contained in the file `movies.csv`. Each line of this file after the header row represents one movie, and has the following format:

    movieId,title,genres

Genres are a pipe-separated list, and are selected from the following:
* Action
* Adventure
* Animation
* Children's
* Comedy
* Crime
* Documentary
* Drama
* Fantasy
* Film-Noir
* Horror
* Musical
* Mystery
* Romance
* Sci-Fi
* Thriller
* War
* Western
* (no genres listed)

## Source
Movie titles are entered manually or imported from <https://www.themoviedb.org/>, and include the year of release in parentheses. Errors and inconsistencies may exist in these titles.

