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


**Neural Network:**

![image](https://user-images.githubusercontent.com/65912577/123803216-b6a4d980-d8b1-11eb-8e28-7c3dd4910c5f.png)


![image](https://user-images.githubusercontent.com/65912577/123803283-c58b8c00-d8b1-11eb-92ff-17a27118e127.png)



**Conclusion:**

Based on user previous scores and recommendations, a selection of new beers can be recommended to the user. The most recommended style of beer seemed to be the Pale Lager, which was the top recommendation for almost 80% of the reviewers. 


**Future Work:**

By using the top scored beers for each style, it weighted the project towards beers with a low review count, which reduced the total number of reviews available. Related to this problem, only the most recent 25 reviews were scraped. These two factors exacerbated the problem of having reviewers and beers with low review counts. Future work would include changing the selection of beers to the most reviewed, instead of the highest rated. 
