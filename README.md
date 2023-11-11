
In this project, Three recommender systems for movies were created. The first system is popularity-based, allowing users to input a genre, minimum rating threshold, and the number of recommendations. It recommends the top movies within the specified genre, prioritizing those with higher ratings and a minimum number of reviews. The second system is content-based, where users input a movie, and the system suggests similar movies based on genres. The third system is collaborative-based, where users input a target user and the number of similar users desired. The system then recommends top movies based on the preferences of these similar users. 

1. Popularity-Based: Users pick a genre, set a minimum rating, and specify how many movies (N) they want. The system suggests the top N movies in that genre with the highest ratings, each having at least the set minimum reviews.

2. Content-Based: Users choose a movie (m), and the system recommends N movies with similar genres to the chosen one.

3. Collaborative-Based: Users provide a target user (u) and the number of similar users (K). The system suggests the top N movies based on the preferences of K similar users to the target user.
