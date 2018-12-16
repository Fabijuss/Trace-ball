# Trace ball
 ---
### Contents
I. [Epics and User Stories](#epics-and-user-stories)  
&nbsp;I.1 [Epic](#epic)  
&nbsp;I.2 [User Stories](#user-stories)  
&nbsp;&nbsp;&nbsp;I.2.1 [Enemy](#enemy)   
&nbsp;&nbsp;&nbsp;I.2.2 [Player](#player)   
&nbsp;&nbsp;&nbsp;I.2.3 [Lives](#lives)   
&nbsp;&nbsp;&nbsp;I.2.4 [Game area](#game-area)   
&nbsp;I.3 [Non-functional Requirements](#non-functional-requirements)  
&nbsp;&nbsp;&nbsp;I.3.1 [Graphics](#graphics)   
&nbsp;&nbsp;&nbsp;I.3.2 [Restart](#restart)   
&nbsp;&nbsp;&nbsp;I.3.3 [Invulnerability](#invulnerability)   
&nbsp;I.4 [How We Addressed The Requirements](#how-we-addressed-the-requirements)  
II. [Genre](#genre)  
III. [Technical details](#technical-details)  
&nbsp;III.1 [Platform](#platform)  
&nbsp;III.2 [Programming Language/Enviroment](#programming-language)  
&nbsp;III.3 [Programming Challenges](#programming-challenges)  
&nbsp;III.4 [Constructing And Implementing My Code](#constructing-and-implementing-my-code)  
&nbsp;III.5 [Algorithms](#algorithms)  
&nbsp;III.6 [Coding Standards](#coding-standards)  
IV. [Research](#research)  
V. [Project management](#project-management)  
## Epics and User Stories
 ### Epic
  A game in which the player controls a square with their mouse and tries to escape from a chasing enemy square.
 ### User Stories   
 #### Enemy   
 The game should have an enemy which is able to chase the player, the game should be able to detect when the enemy touches the player so that they can lose lives.
 #### Player   
 The player should be able to control their square by using a mouse, this should be responsive and accurate to ensure the game is playable.
 #### Lives   
 The player should be able to lose lives whenever they are touched by the enemy square, if they are touched 3 times they lose the game.
 #### Game area   
 The game should be set on a specific size of game canvas; this will ensure that the gameplay experience is consistent.
 ### Non-functional Requirements   
 #### Graphics   
 The game should have some graphics, so that the enemy and the player are distinguishable and so the game has a degree of visual appeal.
 #### Restart   
 When the player loses all of their lives, the game should be able to restart. 
 #### Invulnerability  
 When the player is touched by the enemy, there should be a short period of time where the player cannot be damaged again. This is in order to prevent the player from losing very quickly from consecutive touches while within the collision area of the enemy.

 ### How We Addressed the Requirements
A plan was created in order to split up the requirements into actionable steps. From this point, these steps were followed by creating a flowchart so that they can be visualised easier, and then implemented into actual code.
## Genre
It is a web-based, single player, player versus computer game.
## Technical details
### Platform
The program was created using no IDE. The entire creation of the application was carried out using the general text editor named ‘Notepad’.
### Programming Language
The programming language for this project is Javascript.
### Programming Challenges
+ Making the enemy follow the player
+ Lives
+ Game borders
### Constructing and Implementing My Code
### Algorithms
### Coding Standards
#### Indentations   
One tab per level of indentation.   
Example:   

    x = 1   
    y = 1   
    code
    {
     if x == y:   
      do something() if true:   
    }

#### Naming    
camelCase with no underscores between words.   
Example:   

     variableName   
Not:   

     variable-name   

#### Comments   
Should be above the code, using // to comment. No inline comments.  
Example:  

    // this is code   
    code()   
#### Spacing   
There should a space separating every element unless there is an operator.   
Example:  

    var space = 1   
    division = numberOne/numberTwo   
Not:   

    var space=1   

## Research
## Project management
