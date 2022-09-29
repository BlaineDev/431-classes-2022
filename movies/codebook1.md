# The `movies_2022_09-08` code book

On our Shared Google Drive in the `favorite_movies` subfolder, you'll find a data set (a Google Sheet called `movies_2022-09-08`) containing the 159 films that people taking the 2020, 2021 or 2022 versions of 431 identified as their "Favorite Movies" in response to [the Syllabus, Section 14](https://thomaselove.github.io/431-syllabus-2022/movies.html). For each movie, I gathered several additional characteristics from the [Internet Movie Data Base](https://www.imdb.com/) (IMDB).

The data set is called `movies_2022-09-08` and here is a brief codebook describing the variables presented there:

Variable | Sample Value | Explanation
:--------: | :------------: | ------------------------------------------------------------------------
`film_id` | 7 | code (1-115): arranges in alphabetical order by title, ignoring starting "The" or "A"
`film` | Avengers: Endgame | film title according to IMDB
`mentions` | 3 | (`list_2020` + `list_2021` + `list_2022`) students who named this film across 2020 and 2021
`list_2020` | 1 | # of students who chose this film as their favorite in Fall 2020
`list_2021` | 1 | # of students who chose this film as their favorite in Fall 2021
`list_2022` | 1 | # of students who chose this film as their favorite in Fall 2022
`year` | 2019 | year film was released
`length` | 181 | length of film (in minutes)
`mpaa` | PG-13 | Motion Picture Association of America's rating (G, PG, PG-13, R, NC17 or Not Rated)
`imdb_categories` | Action, Adventure, Drama | Film Categories specified by IMDB (up to 3)
`imdb_ratings` | 919813 | Number of Star Ratings (IMDB) 
`imdb_stars` | 8.4 | Weighted Average Rating (IMDB) 
`imdb_pct10` | 33.9 | percentage of raters on IMDB that rated the film at the maximum level (10 stars)
`dr_love` | Yes | Whether or not Dr. Love has seen the film in its entirety (Yes or No)
`imdb_link` | [Weblink](https://www.imdb.com/title/tt4154796/) | link to the IMDB page for the film

- IMDB updates regularly, so the results may look a little different now.
- The `imdb_stars` result is actually a proprietary weighted average. "IMDb publishes weighted vote averages rather than raw data averages. Various filters are applied to the raw data in order to eliminate and reduce attempts at vote stuffing by people more interested in changing the current rating of a movie than giving their true opinion of it. The exact methods we use will not be disclosed." 
    - The arithmetic mean and median rating are also available, if you click through the `imdb_ratings` value.
