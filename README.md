# RecommenderSystem
Book recommender system due to the course Information Retrieval and search engines on the 7th semester.
It is using the Book-Crossing dataset ((http://www2.informatik.unifreiburg.de/~cziegler/BX/)). The zip consists of 3 files one for users, 
one for books and one for book-ratings. Doing some preprocess in data and then according to 3 best most ranked books from user it makes
a 'profile' for user. Then using two different functions to calculate a score(similiraty) between [0,1] 
using bookAuthor equality, year published difference and  Keywords with two different metrics between Keywords Jaccard and Dice Coefficient 
and it returns the top ten books which he has not ranked yet. 
