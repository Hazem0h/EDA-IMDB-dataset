## Introduction


This dataset has about 10 thousand records of movies, as well as information about:
* Movie budget
* Movie Revenue
* Cast 
* Director
* Production Company
* Rating
* Popularity
* Genre

From this extensive dataset, it would be interesting to investigate different factors and their effect on the movie's revenue, rating and popularity. As such, our exploration will try to answer the following questions:
* Does high revenue indicate the movie was good (in terms of ratings) ?
* What is the relationship between the voting average and revenues?
* Does popularity correlate with the voting verage ?
* Which genres achieve the highest revenues ?


## Conclusion
This dataset included about 10 thousand records of movies from different genres and form different times across the 20th and 21st century. We wanted to explore the distributions of different variables, as wellas the relationship between them. Specifically the revenue, the popularity, the average voting score and the genre. <br>
One might think that the average voting is a better predictor of a movie's financial success, rather than its popularity. Another might thinnk otherwise. In such cases, it is better for all to sit down, and let the data talk through analysis. Although, we should hear what the data says, with a pinch of salt, taking care of any limitations within the analysis or the data itself.

After performing some data cleaning, and putting the data into a clear, clean format, we reached the following results:
* There is a positive correlation between the revenue and each of popularity and the average voting
* The correlation of revenue with the popularity is **significantly stronger** than that with the average voting. So a successfull movie is more likely to be popular than it having a good average rating
* The action genre is the highest grossing movie genre. (on total Not per movie)<br>
Note: The correlation doesn't mean causality. These results do not tell us which factor caused the other.

#### Limitations:
* First and formeost, all of the analysis is done on  a sample, and not on the population. So, any conclusion should be conveyed within this context
* Nearly 50% of the records had missing values in the revenue column. This adds uncertainty to our results that could have changed if the data wasn't missing
* We didn't account for inflation due to different release times of movies. That would significanlty affect the revenues especially if a movie is really old