#dsc-capstone


**Data Source:**

Beer reviews taken from https://www.beeradvocate.com/

Total Beers: Over 9000 different beers scraped. The top 100 rated beers for each style were picked for this project. 

Total Reviewers: Over 15000 unique reviewers

Total Reviews: 150,000 reviews scraped. The most recent 25 reviews for each unique beer was scraped. 

**Data Analysis:**
Average User Ratings for all Reviews

![image](https://user-images.githubusercontent.com/65912577/123800136-96bfe680-d8ae-11eb-922b-f304322c73c8.png)

Worst Reviewed Beer Styles

![image](https://user-images.githubusercontent.com/65912577/123801147-9e33bf80-d8af-11eb-9ba9-129b29d5d5a2.png)

Median ABV for beer styles

![image](https://user-images.githubusercontent.com/65912577/124306390-f1b24180-db2b-11eb-8f0d-1cb6f7019ad1.png)


**Neural Network:**

![image](https://user-images.githubusercontent.com/65912577/123803216-b6a4d980-d8b1-11eb-8e28-7c3dd4910c5f.png)


![image](https://user-images.githubusercontent.com/65912577/123803283-c58b8c00-d8b1-11eb-92ff-17a27118e127.png)


**Surprise Library**

Using the surprise library, the average of the physical ratings given by the users (smell, taste, feel, & look) provided the highest RMSE of .47 while the MAE remained around 0.32. 
However, the given user rating still remained OK with a RMSE of 0.41 and the lowest MAE of 0.28. The lower MAE isn't unsurprising given the data was skewed towards a higher user rating, while the other ratings weren't directly affected. Although a higher user rating could lead towards higher physical ratings as well.

**Conclusion:**

Based on user previous scores and recommendations, a selection of new beers can be recommended to the user. The most recommended style of beer seemed to be the Pale Lager, which was the top recommendation for almost 80% of the reviewers. 


**Future Work:**

By using the top scored beers for each style, it weighted the project towards beers with a low review count, which reduced the total number of reviews available. Related to this problem, only the most recent 25 reviews were scraped. These two factors exacerbated the problem of having reviewers and beers with low review counts. Future work would include changing the selection of beers to the most reviewed, instead of the highest rated. 
