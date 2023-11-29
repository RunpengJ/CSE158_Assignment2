# UCSD CSE 158 Assignment 2

Collaborators: Runpeng Jian, Zheng Zeng

Hypothesis: 
1. **Business-Uploaded Images**: The user rating is positively correlated with the number of images uploaded by the users. businesses with more uploaded images (which could be represented by the pics field or a similar field not shown in your sample) tend to receive higher ratings, possibly because more images could imply better transparency or visual appeal.)
2. **Review Text**: The sentiment or length of the review text is correlated with the rating given by the user.
3. **Business Average Rating**: Users' ratings are influenced by the average rating of the business. Users might be biased by the existing average rating of the business (which might be calculated using the rating field across multiple reviews). For instance, a business with a high average rating might continue to receive high individual ratings due to user expectations or perception.
4. **# of Response to Reviews**: The presence or quality of a response from the business to a review affects subsequent ratings. If the resp field indicates whether a business responded to a review, this could influence future ratings, as a business that actively responds might be perceived as more customer-friendly.
5. **Number of Reviews**: Businesses with more reviews have a better-established reputation, which might reflect in their ratings.
6. **Users Average Rating**: Users who generally give high or low ratings across different businesses tend to maintain similar rating patterns for each review.