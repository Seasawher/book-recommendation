# Book Recommendation Engine using KNN

In this challenge, you will create a book recommendation algorithm using K-Nearest Neighbors.

You will use the Book-Crossings dataset. This dataset contains 1.1 million ratings (scale of 1-10) of 270,000 books by 90,000 users.

## Specifications

* If you graph the dataset (optional), you will notice that most books are not rated frequently. 

* To ensure statistical significance, remove from the dataset users with less than 200 ratings and books with less than 100 ratings.

* Create a function named `get_recommends` that takes a book title (from the dataset) as an argument and returns a list of 5 similar books with their distances from the book argument.
