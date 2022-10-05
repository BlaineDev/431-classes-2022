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

# Raw Questions

Proposed Question | Variables Used
:---------------------------------------------------: | :----------------------------------
Has modern cinema gone downhill - Do older films have a higher IMDB rating than newer films due to higher rates of viewership?  | year of release, number of star ratings at IMDB (the `imdb_ratings` variable), weighted average IMDB rating (the `imdb_stars` variable)
Has the length of movies changed over time?  | year of release, Length of the film in minutes
Is there a relationship between movie length and number of star ratings? | number of star ratings at IMDB (the `imdb_ratings` variable), Length of the film in minutes
Are movies made prior to 2000 longer or shorter than movies after 2000? | year of release, Length of the film in minutes
How does IMDB categories and the length of the movie predicts the number of stars it receives? | film categories in the imdb_categories variable, number of star ratings at IMDB (the `imdb_ratings` variable), Length of the film in minutes
What is the relationship between genre and length of movie? | film categories in the imdb_categories variable, Length of the film in minutes
Do dramas have higher ratings than comedies? | film categories in the imdb_categories variable, weighted average IMDB rating (the `imdb_stars` variable)
Are new movies longer in length? | year of release, Length of the film in minutes
Do movies released in 2000 or later have a longer run time than older movies?  | year of release, Length of the film in minutes
Does the length of an action film impact its IMDB rating - an exploratory analysis of action film length and IMDB ratings | film categories in the imdb_categories variable, weighted average IMDB rating (the `imdb_stars` variable), Length of the film in minutes
Do action movies have more IMDB reviews (ratings) than non-action movies?  | film categories in the imdb_categories variable, number of star ratings at IMDB (the `imdb_ratings` variable)
Does a film's category impact the relationship between the film's length and its average star rating? | film categories in the imdb_categories variable, number of star ratings at IMDB (the `imdb_ratings` variable), Length of the film in minutes
Are the average IMDB ratings associated with the number of IMDB star ratings? | number of star ratings at IMDB (the `imdb_ratings` variable), weighted average IMDB rating (the `imdb_stars` variable)
What is the relationship between the year a movie was released and the number of star ratings at IMDB? | year of release, number of star ratings at IMDB (the `imdb_ratings` variable)
How does IMDB rating (imdv_stars) differ between older and newer movies? | year of release, weighted average IMDB rating (the `imdb_stars` variable)
How has  action movies' length changed over time? | year of release, Length of the film in minutes
Does the year of release affect the amount IMDB ratings? | year of release, number of star ratings at IMDB (the `imdb_ratings` variable)
Do movies longer than 2 hours have lower ratings? | number of star ratings at IMDB (the `imdb_ratings` variable), weighted average IMDB rating (the `imdb_stars` variable), Length of the film in minutes
