# Results of Breakout Session 1 (Movies)

Group | Members | First Film They'd All Seen
:----: | :-----: | :-----------------------
The A-List |	6	| The Dark Knight (`film_id` = 26)
The Avengers 	| 6	| Avatar (`film_id` = 5)
The Danger Zone |	6 |	Despicable Me (`film_id` = 29)
Go Mets! | 4 |	Avatar (`film_id` = 5)
Lemon drops	 | 6	| Harry Potter & The Sorcerer's Stone (`film_id` = 55)
The Mellow Cappuccino	| 5 |	Avatar (`film_id` = 5)
Movie Theater Butters	| 6 |	Avatar (`film_id` = 5)
Not Cinephiles | 5 |	Avatar (`film_id` = 5)
No Time for Movies | 6 |	We couldn't find one. (out of 159 films)

# Available Variables

- `year` = year of release
- `length` = Length of the film in minutes
- `imdb_categories` = film categories (up to 3) assigned by IMDB
- `imdb_ratings` = number of star ratings at IMDB 
- `imdb_stars` = weighted average IMDB rating (10 = highest, 1 = lowest possible)

ID | Proposed Exploratory Question | Variables Used
:--: | :---------------------------------------------------: | :----------------------------------
1 | Has the length of movies changed over time?  | year, length
2 | Are new movies longer in length? | year, length
3 | Do movies released in 2000 or later have a longer run time than older movies?  | year, length
4 | Are movies made prior to 2000 longer or shorter than movies after 2000? | year, length
5 | How has action movies' length changed over time? | year, length, (**category**)
6 | What is the relationship between the year a movie was released and the number of star ratings at IMDB? | year, ratings
7 | Does the year of release affect the amount IMDB ratings? | year, ratings
8 | How does IMDB rating (`imdb_stars`) differ between older and newer movies? | year, stars
9 | Has modern cinema gone downhill - Do older films have a higher IMDB rating than newer films due to higher rates of viewership?  | year, *ratings?*, stars
10 | Are the average IMDB ratings associated with the number of IMDB star ratings? | ratings, stars
11 | Is there a relationship between movie length and number of star ratings? | ratings, length
12 | Do movies longer than 2 hours have lower ratings? | *ratings?*, stars, length
13 | What is the relationship between genre and length of movie? | categories, length
14 | Do dramas have higher ratings than comedies? | categories, stars
15 | Do action movies have more IMDB reviews (ratings) than non-action movies?  | categories, ratings
16 | How does IMDB categories and the length of the movie predicts the number of stars it receives? | categories, ratings, length
17 | Does a film's category impact the relationship between the film's length and its average star rating? | categories, ratings, length
18 | Does the length of an action film impact its IMDB rating - an exploratory analysis of action film length and IMDB ratings | categories, stars, length

See [the Class 12 slides](https://github.com/THOMASELOVE/431-classes-2022/tree/main/class12#todays-slides) for Dr. Love's analyses related to (most of) these questions.
