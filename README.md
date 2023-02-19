# DU2.0

Dataset Content
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.</p>

Inspiration
Understanding what content is available in different countries
Identifying similar content by matching text-based features
Network analysis of Actors / Directors and find interesting insights
Is Netflix has increasingly focusing on TV rather than movies in recent years.

Data Cleaning
Drop id column
Drop dublicate shows
create a new column shows the number of cast in each row
we have 10 missing rows in rating column, replace them by the mode
for the missing rows in added_date column, replace them by January 1,{release_year}
I think we can not replace missing rows in column country by other countries, but we can use genre to
identify this country ex: replace missing rows by japan for Anime
convert the date_added column from object type to datetime
