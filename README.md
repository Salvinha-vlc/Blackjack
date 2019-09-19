<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Python Casino Blackjack 
Salvador Rocher Espinosa

Data Analytics, Barcelona, July-19

## Content
- [Project Description](#project-description) 
- [Rules and Settings](#rules and settings) 
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description

This projects presents a single-player blackjack game where one play against the dealer (computer). Games are in my opinion a good way to kick things off in Python, and Blackjack gathers the conditions to practice loops, functions, nested functions, and logical conditions all together in the mix. Besides it is fun! Try to beat the casino while managing your bankroll.

<a name="rules and settings"></a>

## Rules and Settings

This game is a somewhat simplified version of what the casino Blackjack is in real life. Here are some details.

First, the script will ask you how much cash you want to draw to sit on the Blackjack table. Minimum is 50€, max is 500€. Then, you will have to bet before the cards are dealt - minimum 50€ and maximum as much money as you have left. 

After this, 2 cards are dealt face up to both the player (you) and the dealer. The face value of each card is, in case of them being numbers, its respective number in points, and in case of figures, if it is not an ace, 10 points, and if it is an ace, the script will ask you what you want to do with each of them (in case there is more than 1 in your initial hand), that is, whether you want to make them to count 1 or 11 points. The goal is to get as close to 21 points but without exceeding it. You play first, that is, you can either stick or ask for more cards, this time, in each subsequent round you will just be dealt with 1 card. If your hand goes beyond 21 points, you automatically lose your bet. 

If you have stuck before exceeding 21 points or just got the 21 points, dealer is programmed to continue to play as long as its hand's value is below 17 points or as long as its hand is lower than yours.

Whenever the results of the round are a tie at the end, the pot is split which means you get your initial bet back, no casino rack/commisions have been defined in this game.

If there is blackjack in the initial showdown:

- Loss/gain is 1.5x the bet amount (as long it does not exceed your bankroll in case of loss)
- If there would be a tie in the initial showdown to 21, dealer wins.

<a name="workflow"></a>

## Workflow

1º Understanding the game and defining the rule boundaries of my version
2º Structuring the sequence of actions that comprise the game
3º Drafting the code as per the structure chosen
4º Writing the code in a basic version
5º Developing the code to an enhanced version
6º Preparing the slides and the presentation
7º Presenting the project


<a name="organization"></a>

## Organization

I first drafted a plan of the code on paper (pseudo-code) and set the sequence of tasks to follow in trello.

<a name="links"></a>

## Links
Include the links to your repository, slides and trello. Feel free to include any other links associated to your project. 

[Repository] https://github.com/Salvinha-vlc/Project-Week-1-Build-Your-Own-Game   
[Trello] https://trello.com/b/aRH6SA2E/proyecto-1  
