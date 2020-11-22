# Movie Data Analysis


![movie gi from giphy](https://media.giphy.com/media/VxbP9tLeKzazm/giphy.gif)



## Introduction:

Microsoft has decided to create a new movie studio, but they want to gather information to better understand the movie industry and what type of films to create.

Movies data were gathered to study, process, analyze, and make a decision to help Microsoft how they should start their movie studio.

The recommendation is going to be based on the best studio, movie's production budget, which genre makes a lot of money, and the most popular genre.

### The Data

In the folder `zippedData` are movie datasets from:

* The Movie Database (TMDb)
* Internet Movie Database (IMDb)
* The numbers (TN)
* Box office Mojo (BOM)

These datasets were provided to me as part of this project by Flatiron School.




## Analysis

The following questions were asked to analyze the data:
1.	What are the top ten studios in the film industry?
2.	Is there any relationship between the movie’s production budget and its revenue?
3.	Is there any relationship between the movie’s production budget and its profit?
4.	Which genre of movies is the most profitable?
5.	Which genre of the movie is the most popular?


   

## Recomemendations

1. Best Studios to contract with:20th Century Fox, Warner Bros. and Universal Pictures are top three studio to partner with.
2. More movie production budget, more in revenue. 
3. A higher production budget gets higher profit.
4. Profitable Genre: Adventure, Action, and Comedy.
5. Popular Genre: Drama, Comedy, and Action.


## Limitation:
- I noticed that the data from Box office Mojo (BOM) is not up to date, which limits me to make another comparison between the domestic gross and the foreign gross.
- The small size of the datasets provided.

## Observations:

- I found out while I was on the TMDb website that there was a perfect way to merge the data with IMDb using tconst because each movie's link has a tconst inside the link. example: https://www.themoviedb.org/redirect?external_source=imdb_id&external_id=tt2975590 

- I also found out that on the TMDb website that each genre is associated with Id number, so it was easier to get the name of the genres from a dictionary than merging with another data frame to minimize the error  https://www.themoviedb.org/talk/5daf6eb0ae36680011d7e6ee

## Future work:
- I noticed that the data from Box office Mojo (BOM) is not up to date, which limits me to make another comparison between the domestic and the foreign gross. so I would like to use APIs to get more accurate data.
- Use APIs to get other movie datasets like Rotten Tomatoes
