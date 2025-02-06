# CSCI 3412 Project 3 - Star Traversal

For this project we need to read in the HYG Database, the HYG Database is in comma separated value (CSV) format. we don’t 
need to write your own CSV parser, Just choose one for the programming language we are using. We need to use the hygxyz.csv 
file that contains the x, y, and z rectangular coordinates for each star in the database. We then need to plan a trip to visit all the known stars, per the HYG Database, within some specified radius
of our solar system. [We're assuming we have a technology that lets us jump instantaneously between
stars.] We don't care about an optimal shortest path between the stars, but we don't want to just randomly
jump between stars either. Instead, starting at Sol (our sun), we want to jump to the nearest star (that is
within our specified radius of Sol) and continuing to the next nearest star that hasn’t been visited until
we have visited all the stars that are within our specified radius of Sol. This greedy algorithm is not
guaranteed to give us the shortest path.
