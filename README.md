# Movie-Direction

# Business Understanding
Microsoft is venturing into the realm of the big screen and is seeking information on how to create big picture movies that will dominate the box office. Operating in the movie-making space can yield boundless rewards but can also bring enormous losses. When evaluating the problem of losing because of a poor creation of a movie, there are three errors that can occur that will guarantee a loss: a lack of a genre, a small budget, and the wrong release date. A lack of a desirable genre will leave the consumer wondering why they should spend their hard-earned money to go to the movies to watch the film. A small budget will restrict who can be brought in to write, direct, and act in the movie creating a strain on the Big 3. If a film lacks the Big 3 there is a chance the movie will be relegated to a B-list movie. Releasing a movie during a time of the year when consumers cannot get to the theatre can destroy a movie’s potential even if the first two problems are alleviated.

# Technical Summary
Throughout this movie modeling process, many different coding methods were performed. The IMDB Movie Basics served as the baseline for the data used, and data from IMDB Ratings, Movie Gross, and Movie Budgets were used to round out the data collection process. In order to get to the dataframe labeled “df” there were numerous steps taken to merge and clean the data. For the final output, I was able to compare total gross with the movie budget and received a clear understanding of the impact a good movie budget can bring. Next, I compared movie budget to movie ratings and concluded that the data was too close to distinguish a difference great enough to have an impact. Next, I compared the top twenty genre combinations and total gross and concluded that two genre combinations lead by a wide margin. Also, I concluded that action and adventure are genres that dominate the top twenty genre list. Finally, I compared the release month to the monthly total gross mean and found that the summer months are best for releasing movies and maximizing profits.

# Data Gathering
I gathered movie data using pandas and sqlite3. For more information on how I gathered the data, please look at my data gathering section in the main notebook.

# Data Understanding
This data represented over 146000 movies released between 2010-2115. The data was not complete, but had exstensive data betwen 2010-2020 that gave a clear picture of the movie industry.

# Modeling
Several models were created to try and alleviate the problem. First, I used a model to look at the impact a movie budget has on a movie's total gross.

![](Images/Graph%201.png)

The bar graph shows that the higher the productuion budget the higher the total gross return. The range of 328M - 369M returns the highest return on investment with 369M - 410M returning the second highest amount.

Second, I look at the total gross for the top twenty genre combinations.

![](Images/Image%203.png)

The bar graph shows that the top genre from a total gross standpoint is 'Action, Adventure, Sci_Fi' coming in over 600 million followed by 'Action, Adventure, Animation' and 'Action, adventure, comedy'. Action is accounted for in 75%, Adventure is accounted for in 55%, and The 'Action, Adventure' combination accounts for 40% of the top_twenty_genres.

Finally, I look at the average total gross for each month of the year. 

![](Images/Graph%204.png)

The bar graph shows that the summer months are highest grossing time to release a movie with the latter part of winter being the second highest grossing time of the year.

# Conclusion
Throughout this movie data modeling process, many different coding iterations were run. In the end, the iterations that yielded the best results were the movie budget compared to total gross, top twenty genre combinations compared to total gross, and release month compared to total gross. The movie budget compared to total gross yielded the result that $328-$369 Million will return the most for Microsoft investment. Next, the top twenty genre combinations compared to total gross yielded that action and adventure are the genres best suited to maximizing a generous return on investment. Finally, the release month compared to total gross yielded that the summer time is best suited to release a movie followed by the winter. All these reasons support why this model would be a great benefit for Microsoft as they venture into the space of movie creation.