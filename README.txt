Introduction:

Let me introduce you my investigation of TMDB Data.
Personally I'm very interested in movies & series. Therefore it's my intentiton to explore & analyze this dataset of movies and answersome questions that I will show in a few lines below.



Description of the dataset:

First of all, the data itself belongs to the official website of The Movie Database (TMDB) with the url:
https://www.themoviedb.org

The raw dataset contains more than 10,000 movies, including user ratings, budget, revenue, director, actor, genre etc. that I will alsoshow you in a few line below.

It comes with a detailed shape of 10866 rows and 21 columns.



Questions that will be answered:

1.Do the films with the highest budgets also bring in a high revenue? And what's about the winnings?

	a) What are the most top10 movies with the highest budgets?

	b) What are the most top 10 movies with the highest revenues?

	c) What are the most top 10 movies with the highest winnings?

	d) What are the most top 10 movies with the lowest winnings?

	e) What are the average budgets, revenues and winnings by years?

	f) Is there a correlation between budgets and revenues?

	g) Is there a correlation between budgets and winnings?

	h) Is there a correlation winnings and revenues?


2.Does the genre of a movie affect it's running time?

	a) What are the average running times of films over the years?

	b) How is the distribution of the genres regarding to the movies?

	c) What is the distribution of runtimes regarding to the different genres?


3. Which specific genres brings the most winnings?

	a) What are the budgets of movies by genres?

	b) What are the revenues of movies by genres?

	c) How big are the budgets and revenues of each movie by genres?

	d) How big are the winnings and revenues of each movie by genres?

	e) Does the revenues also got a strong correlation to winnings by movie genres?


4. Bonus Questions:

	4.1 What are the characteristics of the most casted actor?
		
		a) What are the top 10 actors?

		b) Was he only in high-budget films during his career?

		c) What is the distribution of Robert De Niro's average votings for his movies?

		d) What are the mean average votings from Robert De Niro by different movie budget classes?

	4.2 What is the distribution ov movie runtimes within their runtime labels?

	4.3 What is the distribution of movie voting counts labels?

	4.4 What is the distribution of rating classes groubpy voting counts labels?

	4.5 Who are the top 20 production companies of movies with "many" counted votes and a "premium" budget?



Conclusions at the end of the investigation:

	Limitation:

		- There are a large number of zeros in the Cast, Director, Keywords, Genre and Production Companies columns where they havebeen replaced with the word "Unknown" to save as much data as possible with budget or revenue.
		
		- Movies with 0 budget (54.43%), 0 revenue (55.37%) or with 0 runtime (0.29%) simply make a huge amount of useless data. For thisreason, only 35.47% of the data rows are left (not counting duplicate rows). Under real conditions I would search for anotherdataset to fill in the missing data via join.

		- So with this limitations, only 3854 rows remain in the cleaned dataset. This is not as representative as the old data set, but on the otherhand, the old data set would have had a large impact on various statements and results.


	Conclusion to each main question:


		Question 1:

		- The films with the highest budget does not bring in automatically the highest revenues. Good example for that is the movie "TheWarrior's Way".

		- The correlation between higher revenues and winnings is pretty clear to see.


		Question 2:

		- There is a range of different runtimes regarding to the specific genres.

		- The highest average running times are found in the genres 'History', 'War' and 'Western'.

		- Films with a shorter average running time are more often found in the genres 'Horror', 'Family', 'Animation' or 'TV Movie'.


		Question 3:

		- The genre with the most winnings (180.18 Million) is 'Animation'.

		- We can clearly see the same correlation as in question 1, but now with the averaging of revenues and winnings across differentgenres.


		Bonus Question with Robert de Niro:

		- He is the actor with the most movies (52) in this datasset.

		- He has acted throughout all different amount of budgets films until the end.

		- But his focus has been on higher budget and also premium movies with the same percentage of 36.54%.

		- The average vote ranges from a minimum of 4.00 to an average of 6.40 to a maximum of 8.10.

		- The average rating in each budget class ranges from low 6.77 to medium 6.72 to higher 6.44 and finally to premium 6.1.



So enjoy reading my research and let me know what your opinion is on the subject or my code etc. I would love to hear it :-)


Created by Stefan M.