# Fast-Approximate-Search

## Approximate Nearest Neighbours Search

Sometimes, when we are processing a user query, it may be **acceptable to retrieve a "good guess"** of 
nearest neighbours to the query **instead of true nearest neighbours**. In those cases, one can use an algorithm which doesn't guarantee to return the actual nearest neighbour in every case, **in return for improved speed or memory savings**. Thus, with the help of such algorithms one can do a **fast approximate search in a very large dataset**. Today we will expore two approaches based on graphs and trees.

This is what we are going to do in this repo: 

1. Build a *navigable* small-world graph;
2. Build a k-d tree;
3. Try [Annoy](https://github.com/spotify/annoy). 
