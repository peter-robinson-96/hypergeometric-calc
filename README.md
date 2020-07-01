# Hypergemetric calculator

I wanted to build a free tool for making complex calculations in the context of game design, where the probability of drawing certain combinations of things over a game has an impact on balance, and how the game feels to play. This balance and game-feel are easier to manipulate and design if a designer can calculate these probabilities. 

My goal is to have something very simple to use which does not require an understanding of the calculations involved, only an ability to identify what you want to know.



## Separate client/server

The boilerplate is also set up to host the client using `webpack-dev-server` with hot module reloading etc. To use this method, in one terminal run:
```sh
npm run client
```
and in the other:
```sh
npm run server
```
The client will be available on http://localhost:8080 and the server on http://localhost:3000. Note that you will still need to manage CORS between the two, as they are on different ports.

