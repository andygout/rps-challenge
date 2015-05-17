# RPS Challenge: Rōnin Badge Test

TO DO
-----
*   Round wins are not being counted properly and so game continues after goal has been reached, i.e. 3/2 wins...
*   Scenario in which no radio box is checked - a nil value is passed; should redirect to choose page.
*   Add game over scenario tests (will require mocks (or Cucumber equivalent - before/after hooks? - apply elsewhere where required)):-
    Scenario: Ending the game and starting over
    Given I am on the game over page
    Then I should see "Game Over"
    When I follow "Play Again?"
    Then I should see "Enter your name"
*   N.B. choose.erb radio button to see how 'id' must be added to make Cucumber features test work.
*   Function to show reasoning for outcome, i.e. 'scissors cuts paper / paper covers rock / rock crushes scissors' - perhaps use hashes with key being phrase and element being array - compare two choices again the element array; will be especially useful when expanding to Spock and lizard.
*   Two player mode.
*   Rock paper scissors lizard spock mode.

Instructions
-------
* Challenge time: Friday, the entire day + the weekend if you need it
* Feel free to use google, your notes, books, etc but work on your own
* You must submit a pull request to this repo with your code by 9am Monday morning

Task
----

Knowing how to build web applications is getting us almost there as web developers!

The Makers Academy Marketing Array ( **MAMA** ) have asked us to provide a game for them. Their daily grind is pretty tough and they need time to steam a little.

Your task is to provide a _Rock, Paper, Scissors_ game for them so they can play on the web with the following user stories:

```sh
As a marketeer
So that I can see my name in lights
I would like to register my name before playing an online game

As a marketeer
So that I can enjoy myself away from the daily grind
I would like to be able to play rock/paper/scissors
```

Hints on functionality

- the marketeer should be able to enter their name before the game
- the marketeer will be presented the choices (rock, paper and scissors)
- the marketeer can choose one option
- the game will choose a random option
- a winner will be declared


As usual please start by

* Filling out your learning plan self review for the week: https://github.com/makersacademy/learning_plan (if you haven't already)
* Forking this repo
* TEST driving development of your app

**Rōnin BANZAI!!!!**

## Bonus level 1: Multiplayer

Change the game so that two marketeers can play against each other ( _yes there are two of them_ ).

## Bonus level 2: Rock, Paper, Scissors, Spock, Lizard

Use the _special_ rules ( _you can find them here http://en.wikipedia.org/wiki/Rock-paper-scissors-lizard-Spock_ )

## Basic Rules

- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock
