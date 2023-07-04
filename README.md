# AirlineUsingGraph

This is a program that utilize Graph data structure to construct airline system. 
It uses Depth First Search (DFS), and Breadth First Search (BFS) to find the shortest path from one airport to another.

# Inner Design
There are six cities:       
- `San Francisco`
- `Austin`
- `New York`
- `Mumbai`
- `Indore`
- `Dewas`

Each city is represented as a vertex in a graph with following characteristics:
- `index`: index of the city
- `name`: name of the city
- `code`: code of the city

The program starts by adding the six cities and connecting the cities by adding edges between the cities.<br/>
Then, call DFS and BFS to find the connected cities. <br/>
Here, we can notice the difference between how BFS and DFS works.<br/>
<img width="244" alt="Screen Shot 2023-07-04 at 6 31 52 PM" src="https://github.com/dj980907/AirlineUsingGraph/assets/108609222/26009eb7-3585-4160-bfda-f08468cb6a99">
<img width="244" alt="Screen Shot 2023-07-04 at 6 32 07 PM" src="https://github.com/dj980907/AirlineUsingGraph/assets/108609222/030b05e8-4ff0-4f76-ada5-2d0f7b3ecb8a">
