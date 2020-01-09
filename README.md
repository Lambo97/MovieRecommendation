# Movie Recommendation

What movie should I watch to tonight? A very common, yet personal question, that movie recommendation systems try to answer. In our project, we want to get insights on the way users rate movies, predict ratings for a movie and identify what influences that rating.

Most recommendation algorithms are based on single value decomposition. We will approach this task on a network-basis, using similarities of movies and users as edges, these similarities will be generated from similar rating behavior, as well as specific features of movies.

The main focus will be on an approach where the existing ratings of a user will be used on a network with movie nodes. The remaining ratings of this users are hoped to be recovered by means of the TV regularization.
A second approach will look at the possibility to get information on the movie ratings by every user using the user neighborhood and build a weighted rating prediction based on connected users, therefore a graph with users as nodes will be created.

## About

This project has been realized for the course EE-558 : A network tour of data sciences at EPFL (fall 2019).

Lukas De Loose </br>
Niklas Glaser</br>
Maxime Lamborelle</br>
Nils Ter-Borch</br>

