# RecommenderSystem
Book recommender system due to the course Information Retrieval and search engines on the 7th semester.
It is using the Book-Crossing dataset ((http://www2.informatik.unifreiburg.de/~cziegler/BX/)). The zip consists of 3 files one for users, 
one for books and one for book-ratings. Doing some preprocess in data and then using some functions to calculate a score(similiraty) between [0,1]
with different metrics between Keywords like Jaccard and Dice Coefficient and it returns the top ten books which he has not ranked yet 
according to 3 best most ranked books from user.
