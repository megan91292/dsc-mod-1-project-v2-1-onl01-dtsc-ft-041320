# An Analysis of Movie Success at the Box Office

<img src ='images/readme image.jpeg' width =150%>


<h2>Purpose</h2>
The purpose of this project is to investigate what has the biggest impact on the success of a movie at the box office. 




<h2>Data Description</h2>
The Repo is split up into 5 folders 

```
Questions:
* Question 1 - Correlation between Budget and Revenue.ipynb
* Question 2 - Does ROI change based on budget categories.ipynb
* Question 3 - Does the day of the week and month of release affect gross revenue?.ipynb
* Question 4- ROI & Gross Revenue by Genre.ipynb
* Question 5 - Top 250 Grossing films of last decade.ipynb

Cleandata:
* genredf.csv
* movierevenue.csv
* randomgenreallocated.csv
* Revenue_Budget_Genre


Data Cleaning Notebooks:
Contains notebooks where datacleaning was done
* Using TMDB API to get Genre names and also making table.ipynb
* Randomly Allocated Genre.ipynb
* Cleaning Data Movie Revenue.ipynb
* Web Scraping and Cleaning.ipynb


ZippedData:
* bom.movie_gross.csv
* imdb.name.basics.csv
* imdb.title.akas.csv
* imdb.title.basics.csv
* imdb.title.crew.csv.gz
* imdb.title.principals.csv
* imdb.title.ratings.csv.gz
* rt.movie_info 2.tsv
* rt.movie_info.tsv
* rt.movie_info.tsv.gz
* rt.review.tsv
* rt.reviews.csv
* rt.reviews.tsv
* rt.reviews.tsv.gz
* tmdb.movies.csv
* tmdb.movies.csv.gz
* tn.movie_budgets.csv
* tn.movie_budgets.csv.gz

Images:
* Contains array of images that are use in the powerpoint pdf

```





<h2>Question 1: Is there a Correlation between Budget and Revenue?</h2>
<h3> How has this Changed over the decades?</h3>

<h5> Findings:</h5>
With a correlation coefficient of 0.75, there is a strong relationship between budget and revenue. It is also interesting to note that this relationship has strengthened throughout the last 4 decades. Going from 0.39 in 1980s to 0.79 in the 2010s!!

<h5> Recommendations:</h5>
Given this information, it is clear that the key is to spend spend spend when it comes to revenue generation is all you are worried about.

<img src ='images/Question1a'>
<img src ='images/Question1b'>




<h2>Question 2: Does ROI vary by Budget Category?</h2>
<h6> Looking at Budgets under $100 million</h6>
<img src ='images/Question2'>

<h5> Findings:</h5>
ROI is different depending on budget. Notably, a bigger budget does not always result in a bigger return. 
For Example, the 40-50 million category returns less on average than the 10-20 million category

<h5> Recommendations:</h5>
You should carefully choose your budget when looking for the best return. For example, if you have a budget of 100 million, you should choose to only spend 80-90 to get a better return.

<h2>Question 3: Does the performance of a movie change based on the month of release?</h2>
<h6> Looking at median Gross</h6>

<h5>Findings:</h5>
The Best Month on average for gross revenue has changed throughout the decades. July has stayed constant in the top 2. Notably, December releases have become less and less profitable.

<h5> Recommendations:</h5>
Look at releasing movies in July and November.


<h4> Distribution for Worldwide gross by release month</h4>
<img src ='images/Question3a'> 

<h4> Average Gross Revenue by release month over the past 4 decades </h4>
<img src ='images/Question3b'>

<h2>Question 4: An Exloration of Genres</h2>
<h3>How do gross revenue and ROI change across genres?</h3>

<h5>Findings:</h5>
It is clear from the graph below that ROI varies massively by genre. 

<h5>Recommendations:</h5>
Focus on Animation, Adventure and Mystery films  as these yield the highest return.
Steer clear of Documentaries, as they are loss making, on average.

<img src ='images/Question4a'>



<img src ='images/Q4'>



<h2>Question 5: An Exploration of the Ratings</h2>
<h3>Is there a Correlation between MetaScores and Gross Revenue, IMDB Ratings for the top 250 grossing films at the US box office in the last decade?</h3>

<h5> Findings:</h5>
We found that revenue have no correlation with Ratings.
Also interesting, that there is a high correlation between imdb ratings and metascores, suggesting that critics and individuals have similiar views.

The average Metascore for these films is only 62. It is interesting that only 60% of these films received positive reviews. With 17 of these films receiving unfavourable reviews. Only 22 films gained a Metascore of over 81, achieving must see status.

<h5> Deeper Dive </h5>

Let’s look at the Grown-ups franchise, created by Adam Sandler. The first film, released in 2010, received a Metascore of only 30, meaning it received generally unfavourable reviews from the critics. This didn’t stop its success at the box office though, taking home 162m at the US Box office, ranking 148th for the decade. The sequel, Grown-ups 2, received even worse reviews, with a Metascore of 19, meaning critics voiced their overwhelming dislike for the film. Despite this, it still grossed $133 million at the US box office, ranking 189th for the decade.!

<img src ='images/Q5'> 


<img src = 'images/meta.jpg '>

<h2>Future Analysis</h2>
<ol>
<li>Create a better way of sorting through genres, when movies have multiple genres, potentially using sub categories</li>
<li>Explore the world of Netflix, Amazon Prime etc to see how they have changed the game in terms of film, tv shows and documentaries</li>
<li>Explore the effect awards have on ROI. Do films that win more awards have a higher ROI?</li>
<li>Explore the effects of ratings in more detail! Especially how movies with poor ratings can still perform very well at the box office</li>
<li> Explore the affects of a director or actor on a film </li>
</ol>

