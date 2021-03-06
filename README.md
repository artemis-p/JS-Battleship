# JS-Battleship
A battleship game built in vanilla Javascript. I built this project in order to practise using "while" loops and "if/else" statements in JavaScript. Also, this was a great practise for breaking down a problem and working with pseudocode. The game is mainly played in the console and uses alerts to inform the user of the score and relevant messages. A Battleship V.2 is coming soon... 

## Tech stack used
- Vanilla JavaScript

## High-level design
- User starts the game
    - Game places a battleship at a random location on the grid
- Game play begins
    - Get user's guess
    - Check the user's guess against the battleship to look for a hit, miss or sink
- Game finishes
    - Give the user a score based on the number of guesses


## Game logic
- Declare 3 variables => one for each cell the ship is placed onto
- Declare a variable to store the user's current guess
- Declare a variable to store the number of guesses
- Declare a variable to store the number of hits
- Declare a variable to store if the ship is sunk or not (boolean)
- While the ship is not sunk
    - ask for user's input
    - compare it against the range of numbers which are valid
    - if invalid guess => ask user for another guess
    - else => add it to the guesses
        - if the guess matches a location => add it to the number of hits
        - if hits equeals 3 => set isSunk to true & tell user "You sank my battleship"
- Tell user the score

