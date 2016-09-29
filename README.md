# Elm Tic Tac Toe [![Build Status](https://travis-ci.org/tcmcgee/Elm-TTT.svg?branch=master)](https://travis-ci.org/tcmcgee/Elm-TTT)

## To Play

### Requirements
* A Browser

### Instructions

* Navigate to [this website](http://www.tomcmcgee.me/Elm-TTT/) and play!

OR

* Clone this repository and open `index.html` (in your browser of choice) and play!

## To Develop

### Requirements

* Node
* Elm `npm install -g elm`

### Instructions

#### To Build
* `elm-make ./src/Main.elm`
* Open index.html
OR
* `elm-reactor` then navigate to http://localhost:8000/src/Main.elm

#### To Run Tests

* Run `npm install -g elm` (if you don't have elm installed)
* Clone this repository
* Run `elm package install`
* run `elm-test` to run the fast tests
* run `elm-test ./tests/LongTests.elm` to run every test (including the ones that call minimax)
