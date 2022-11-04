# Amazon_Vine_Analysis
## Summary Overview 
This Analysis was done on reviews given to Video Games through Amazon Vine, a program that pays people to review products. I wanted to know how many Vine and Non-Vine Reviews were included in the different video game reviews, as well as how many Vine and non-Vine reviews gave a 5 star rating. Once I knew how many Paid and Non Paid reviewers gave 5 stars, I was able to find out overall percentages for both sides as well. 

## Results 
I initially gathered all of the reviews into one dataframe and selected reviews with over 20 votes and that had been marked as helpful. 
![Screenshot (50)](https://user-images.githubusercontent.com/108035549/199860732-05de0338-f8fd-4887-a857-55b45834e92b.png)



I then broke that dataframe into two different ones: a paid and unpaid dataframe. 
![Screenshot (51)](https://user-images.githubusercontent.com/108035549/199860759-8597a9ea-b82f-488c-95bb-bc9943b5afe1.png)



![Screenshot (52)](https://user-images.githubusercontent.com/108035549/199860767-47a33816-4f4d-4aa4-8419-9d4b15e9c712.png)


Once I had them broken up, it was easy to run further analysis.

![Screenshot (53)](https://user-images.githubusercontent.com/108035549/199860798-05edab95-420e-439f-bf9b-8d4bd5f7b7ea.png)

![Screenshot (54)](https://user-images.githubusercontent.com/108035549/199860810-5de4a46e-9dff-4bb1-a216-17fecb2c94af.png)

## Final Summary
Of the 94 paid video game reviews, 48 of them were given a 5 star rating. That equates to 51.06% of all paid reviews.

Of the 40,471 unpaid video game reviews, 15,663 of them gave a 5 star rating. That equates to 38.70% of all unpaid reviews.


### AMAZON VIDEO GAME REVIEWS QUICK STATS
Paid Review Quick Stats
- 94 Total Paid Reviews
- 48 5 Star Ratings
- 51% 5 Stars


Unpaid Review Quick Stats
- 40,471 Total Unpaid Reviews
- 15,663 5 Star Ratings
- 38% 5 Stars

In the relatively small sample size of only 94 paid reviews, there was a noticeable bias of 13%, a jump of roughly 1/3rd the unpaid score. One way to check if this is accurate is to view the total number of 1 star, 2 star, 3 star, and 4 star reviews for both paid and unpaid video games. More measuring points would provide a more accurate reading of possible bias.
