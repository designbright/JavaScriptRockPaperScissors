# Rock, Paper, Scissors Game with JavaScript

*Using an if/else block (aka 'conditional statements'), create the logic behind the classic game, Rock, Paper, Scissors.*

## Conditional Statements Overview
* Let you control the “flow” of a program to determine which code runs and when it runs
* Let you make a program behave differently based on circumstances in the program
* Example: User types into a form or the score in a game can change how the program runs

### Conditional Statement Syntax
'If/Else' Conditional Statements are defined by the keywords **if and else**

var answer = prompt(‘What programming language is your favorite?”);

if (condition ) {
 *// code that runs if condition is TRUE*
} else {
  *// code that runs if condition is FALSE*
}

* Inside the ( ) is the condition which is a simple test that is either **true or false**

* Typically with comparison operator like (===)
* Inside the { } code that runs ONLY if the condition is true.
* { } create a ‘code block’
* There is no semi colon at the end of a conditional statement

### Programming with Multiple Outcomes

The **Else/If** Clause

* If the first condition is false, then a second condition is run
* If neither condition is true, you need to run a different code block using an ‘else’ statement after the ‘else if’
* You can have unlimited number of ‘else if’ clauses

**Else/If Syntax**

  if ( ) {

	} else if ( ) {

	} else {
	 *Will only run if  BOTH previous conditions are FALSE*
	}

## Task
Assuming the computer always throws paper, write the conditional statement that will console log out one of the following messages based on what you change the me value too.

* Looks like a tie!
* I win!
* Computer wins!

Keep in mind that:

* Rock beats scissors
* Scissors beat paper
* Paper beats rock

## Project Design Process

Two players:
Computer
Player

### Variables, Outcomes, and Combinations

1. Define game variables

let computer = 'computer';
let player = 'player';

let rock = 'rock';
let scissors = 'scissors';
let paper = 'paper';

    * let computerWins = alert('Computer wins!');
    * let playerWins = alert('Player wins!');
    * let tie = alert('Its a tie!);

2. Define possible outcomes of game
    * rock > scissors
    * scissors > paper
    * paper > rock

3. Write conditional statement

    if (computer === paper) {
      alert('Computer Wins!');
    else{
      alert('Player wins!');
    }
    }
