# Introduction: Movie Rotten or Fresh?

- Here, we'll be analyzing movie reviews in an attempt to determine whether movies are good or bad.  We've downloaded a large number of movie reviews from the [Rotten Tomatoes](http://www.rottentomatoes.com) website.

- Rotten Tomatoes is a meta-review website that aggregates movie reviews from a large number of critics.  Here's what the page for this year's likely [Oscar winner](http://www.rottentomatoes.com/m/the_revenant_2015/) looks like.  Note in particular the section on "Critic Reviews" at the bottom -- that's the content that has been scraped and put in the reviews.csv file.  Also note that each movie is given a quantitative score on the Tomatometer which is used to classify the movie as either Fresh (good) or Rotten (bad).

- The mission is to develop a __classifier__ to determine whether a movie is __Fresh__ or __Rotten__ based on the contents of the reviews given to the movie.  As usual, we'll start out with some exploratory data analysis.
