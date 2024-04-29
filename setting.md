### Parameters
1.  N :Number of birds
2.  W :Length of the side of the square window
3.  x_i :Position of each bird i , i in [1,N]
4.  v_i :Velocity of each bird i , i in [1，N]
5.  r : Radius of view of the birds
 




### Measurement
1. Define a graph where the positions of the birds are vertices, and draw an edge if the distance between two birds is less than r.
2. G :Number of compontents of the graph,defining the number of clusters in the bird flock.




### Hypothesis
1. Fixed N and increasing r lead to a decrease in G.
2. Fixed r and increasing N lead to a decrease in G.



### Behavioral Rules
1. N_i :Neighbors of bird i.
2. v_i(t+1) = mean of v(t). 



