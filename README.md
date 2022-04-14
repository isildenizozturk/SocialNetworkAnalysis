# Complete Network Analysis of Currently Working American Actors & Actresses and Their Filmographies

## Abstract

In this study, we analyzed American actors and actresses who are still acting today based on the data we used. We gathered data which are actors and actresses and their filmography from Ranker and IMDB websites manually. Then we wrote a python code for constructing the network based on these data and modified the code in order to visualize and analyze our network by a Network Visualization tool. We used two files which are the nodes and edges as CSV format, to import into Gephi for visualization.

In many movies, we can see that some actors/actresses act together more than once. Our aim was to determine which American actors/actresses we used as our data are acted together in the same movie, and by using this information we wanted to show the relationship between actors/actresses based on the movies that act together.

## Data Gathering

The data used in this study obtained from the article prepared by the Ranker site and Imdb site. There have been plenty of great American actors and actresses throughout film history so we filtered the data required for this network as American actors and actresses who are actively acting in movies and their filmography.
We collected the data of actors and actresses from the best american actors and actresses working today articles prepared by the Ranker site, and the filmographies of these actors and actresses from the Imdb site manually.

https://www.ranker.com/list/best-american-actresses-working-today/ranker-film

https://www.ranker.com/list/best-american-actors-working-today/ranker-film

https://www.imdb.com/?ref_=nv_home

## Network Construction

We defined a list called Actors and inside of this we kept separate lists containing the movie names of each actor/actresses. After defining this list that contained movies of actors, we defined another list that stored the names of the actors and actresses according to the order of the movie lists in this actor list. Later, we wrote a python code to find the actors who starred in a movie together and defined a dictionary to store the actors and movies that they starred together in this dictionary. 

In the network we have created, the nodes represent the actors and actresses and the edges represent the movies they have starred together, we assumed the actors and actresses who took part in the same movie have a connection with this evaluation, we combined the nodes of these actors with the edges, and we used the number of movies they played together as the weight of the edges between these nodes. By importing the csv library we were able to convert our nodes and edges list to csv format in order to meet the importing data specification of the network visualization tool called Gephi. 

## Network Analysis

In this study, the network analysis was done by dividing it into several parts. By doing this analysis we could more easily understand the functionality of data in the network.

1. Visual Analysis
2. Centrality Analysis
3. Community Analysis
4. Structurel Analysis

 ### If you want to examine the results of our study, you can find the project report from the files.
