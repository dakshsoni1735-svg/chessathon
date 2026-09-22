# CityTrek ♟️

CityTrek is a chess bot built for the **Optiver AI Chessathon**.

It combines **Alpha-Beta pruning** with a **trained neural network** for board evaluation, using the network to supplement search rather than relying entirely on search depth.

### How it works

* Alpha-Beta pruning handles the game-tree search.
* A neural network evaluates board positions.
* The evaluation is used to make better decisions in positions where a shallow search isn't enough.

### Results

* **60% win/draw rate** in competition play
* **1500 peak Elo**

### Built with

`Python` · `Neural Networks` · `Alpha-Beta Pruning` · `Minimax`

Built by **Daksh Soni** & **Rahul Sanklecha** for the Optiver AI Chessathon.
