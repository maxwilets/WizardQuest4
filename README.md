# WizardQuest4

## Demo
This game is deployed on Heroku.  Play it [here](https://tranquil-shore-27347.herokuapp.com/)

## This is the second group project 
   For the project we made a node express app that connects to a mysql database. The goal was to create a
   Point-and-Click style fantasy RPG. It is a full stack game with an express server and a MySql back end.
   Note: This is a duplicate of the original project
   
### Objectives
* MVP
     * A working game that allows players to sign in
     * Keeps track of players progress through the game
     * Logic that determines battle outcome
     * Structured sequences based on the choice made by the user
     
### How it Works
* Once the game is open the user can either sign in, or create a new game
* Once the game is started the player will travel through the game to reach the final dungeon
* They will encounter battles where they will either:
     * Take damage
     * Get away safely
     * Beat the enemies and get some gold
* On the way the player can shop for potions or weapons
     * Potions restore health lost in fights
     * Weapons help get through battles

###
* Errors
     * The game is not perfect it was only built to meet the MVP these are the errors to break the game:
          * Clicking the next button before the dialogue fully loads will dublicate the dialogue
          * Food hasn't been implemented as a game mechanic but can still be purchased in a shop
          * The logic for consuming money or items beyond 0 hasn't been resolved. However if a players' health goes beyond 0 the game               will be over
### Technologies used

- HTML
- CSS
- JavaScript
- Express
- Node
- MySql
- Handlebars
- Sequelize
