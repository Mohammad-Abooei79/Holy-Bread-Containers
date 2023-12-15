# Holy-Bread-Containers
There are 3 holy bread containers with a determined capacity. Holy Father has asked you to move the bread from one container to another and reach from the initial to the target state with minimum cost. 
You are allowed to perform these two actions to change the bread levels in containers:

1- Move bread from one container to another until it is empty or the other reaches capacity. Here the cost  for each move is (it doesn't matter how much bread has been moved): 1 

2- Ask Jesus Christ to make the bread level in one container to the power of the 2 if it doesn't exceed the capacity. Here the cost is: the amount of  bread added to the container + 1

Initial state: [0, 0, 45]

target state: [3, 1, 41]

capacity: [3, 5, 100] 

We want to solve this graph traversal problem with Breadth-First Search (BFS) as an uninformed algorithm and A* as an informed algorithm. We will compare the results in terms of cost, time, and memory usage.
