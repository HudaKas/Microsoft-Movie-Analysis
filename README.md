# Movie Data Analysis


![movie gi from giphy](https://media.giphy.com/media/VxbP9tLeKzazm/giphy.gif)



## Introduction:

Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. They have hired you to help them better understand the movie industry.
Your team is charged with exploring what type of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### The Data

In the folder `zippedData` are movie datasets from:

* The Movie Database (TMDb)
* Internet Movie Database (IMDb)
* The numbers (TN)
* Box office Mojo (BOM)

This dataset were provided to me as part of this project by Flatiron School.



## Analysis

The following questions were addressed:

1. What are the top ten studios in the film industry?
2. Is there any relationship between the  movie’s production budget and  its revenue/ profit?
3. What genre of movies makes the most money?
4. What are the Most Popular Genres?
5. What is the best runnig time?

   

## Recomemendations

1. Based on the data from Box Office Mojo, we can check which studio is doing the best in terms of revenue so Microsoft can contract with. so according to the bellow visualization 

       1. Walt Disney Studios (formerly Buena Vista)
       2. 20th Century Fox
       3. Warner Bros.
       4.Universal Pictures
       5.Sony Pictures Motion Picture Group
       6.Paramount Pictures
       7.New Line Cinema
       8.Lionsgate Films
       9.LG/S
       10.DreamWorks Pictures
So based on the visualization, it is recommended that Microsoft contract with one of the top five studios

2. As we can see in the scatter plot that there is little room between the data points and the regression line, that's mean there is a strong positive correlation between the production budget and the worldwide gross. Also, in the second scatter plot there is a positive correlation between the production budget and the profit. That's mean the more that Microsoft will spend on their movie production budget, the more return and profit will get on their movie. The more they spend on production the more they will get in revenue and profit.


3. After comparing the genres and the profit of the movie, we can recommend to Microsoft what genre of movie is the profitable, so on the top of list is Adventure with the most of the profit followed by Action, and Comedy.

Based on the data from the Internet Movie Database (IMDb), and the data from The numbers (TN) we can see that the top five popular genres are:

       1. Adventure
       2. Action
       3. Comedy
       4. Drama
       5. Sci-Fi

So based on the visualization, it is recommended that Microsoft start their movies with those 3 top genres.

4. After comparing the genres and the popularity the most popular genre is drama followed by comedy, Action, Thriller.

Based on the data from the Internet Movie Database (IMDb), we can see that the top five popular genres are:

       1. Drama
       2. Comedy
       3. Action
       4. Thriller
       5. Horror

So based on the visualization, it is recommended that Microsoft start their movies with those 3 top genres.
4. based on the we can recommend to Microsoft what genre of movie is the profitable

## Limitation:
the unpadted data in BOM, uncorrect number regarding the forien gross which limit me to make another coparrsion between the domestic and the foreign gross


## Future work:
- I noticed that the data from Box office Mojo (BOM) is not up to date so I would like to go and gather more accurate data especially regarding the foreign gross because it is not reflecting the real numbers
- I found out while I was on the TMDb website that there was a perfect way to merge the data with IMDb using tconst because each movie's link  has tconst inside the link. example: https://www.themoviedb.org/redirect?external_source=imdb_id&external_id=tt2975590
- I also found on the TMDb website that each genre is associated with Id number, so it was easier to get the name of the genres from a dictionary than merging with another data frame to minimize the error
https://www.themoviedb.org/talk/5daf6eb0ae36680011d7e6ee 

Action          28
Adventure       12
Animation       16
Comedy          35
Crime           80
Documentary     99
Drama           18
Family          10751
Fantasy         14
History         36
Horror          27
Music           10402
Mystery         9648
Romance         10749
Science Fiction 878
TV Movie        10770
Thriller        53
War             10752
Western         37

