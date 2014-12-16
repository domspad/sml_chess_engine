# SML chess engine

Statistical Machine Learning Chess Engine

## Idea

This is an experiment in the limits of lifting ourselves up by our own bootstraps. 

This repo documents my attempts at creating a chess engine that is only learned how to play chess from playing itself -- with no pre-programmed principles about what are "good" moves. That is:

- When initialized the chess engine should only know the rules of the game 
- The final result is a chess engine that has learned moves based on experience with playing against itself a number of times...


**Questions along the way**

- What do games look like between two perfectly random players?
- What is the most relevant information to glean from these games?
- What model should be used to generate the next move?
- How to introduce randomness into the final result so the engine doesn't choose the same move always for the same board layout?
