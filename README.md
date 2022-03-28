# NLP-Progress-
Sentimental analysis on YELP reviews of Las Vegas Resorts 

In this notebook, I started by doing some exploratory analysis on the given data set 
And found out more information, such as :

1.the given dataset such as there were  46644 reviews , when I calculated by considering non-null review_id because I assumed those are unique. 
2. There are 237 unique hotels and 6 unique travel categories.

I made a histogram plot of hotels and reviews which helped to reach the conclusion that 
overall review ratings on TripAdvisor for Vegas resorts seems to be really high with most resorts rated as 5, which is the highest rating, the Average Rating for a resort in Vegas seems to be 4.03 on TripAdvisor. This means according to TripAdvisor Vegas has very good resort. 

After that I assigned sentiments to texts which gave information about there Polarity and Subjectivity, this helped to reach the conclusion that :
Vast majority of the sentiment polarity scores are greater than zero, means most of them are pretty positive. Vast majority of the sentiment polarity scores are greater than zero, means most of them are pretty positive, moreover the ratings are in align with the polarity score, that is, most of the ratings are pretty high at 4 or 5 ranges.

Then I tried to find degree of correlation between polarity and review ratings which helped me to 
conclude that People who travel Business class give the best reviews as opposed to people who travel solo. 

