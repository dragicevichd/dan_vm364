
![Header Graphic] 
(http://sophiecalhoun.com/images/SUPERPAC.jpg)
#SUPERPAC
Originally a mod of pacman, Superpac is a game that combines elements of pacman, chess, and capture the flag with a political theme.

##ITERATION 1
The first iteration consisted of one player plays superpacman who runs around the board, collecting powerups placed in random locations on the board. Upon collecting a powerup, Superpacman chooses a card from a powerup card deck that gives a random one-use only powerup. Two other players play ghosts who try to get to superpacman.
* The powerups include:
   1. Dash (move faster)
   2. Freeze ghost for 2 turns
   3. Move 2 sq
* Superpacman wins when he collects all of the powerups.
* The game played very imbalanced, and kept flipping between too easy for the ghosts or too easy for superpacman. We implemented several hotfixes including restricted ability of ghosts to move backwards, and tried changing increasing pacman’s speed in relation to the ghosts’.

##ITERATION 2
![Game Board]
(http://sophiecalhoun.com/images/test1.png)
In the second iteration, we significantly changed the gameplay. The game became more like a combination of chess, pacman, and capture the flag. It begins with two flags placed at two opposite ends of the board. It’s a two player game with each player each have 1 ghost (black) and 1 pacman (red). A player wins when your pacman gets the other player’s flag. The ghosts can attack the other player’s superpacman and send them back to their starting point. Each player takes turns moving both their ghost and their superpacman 1 space during their turn. You must move both pieces on your turn. In this version, ghosts can turn around, but cannot move back and forth between two squares to idle in place. We made several hotfixes as we played through this iteration, including:
* Mechanic where when the ghosts collide, the ghosts both must respawn at their original spot.
* Placed opposing game pieces in opposite corners instead of opposite sides.
* Players’ superpacman and ghost cannot remain on the same square.
* Players cannot move your piece back and forth between two squares more than once--this was implemented to prevent idling near the flag.

![Changed Board]
(http://sophiecalhoun.com/images/test2.png)

##ITERATION 3
For the third iteration, we printed out a newly designed board for the game, and playtested to introduce the following changes. We wanted to keep the game primarily strategy based, since players enjoyed the calculative moments of strategy in the game. This is why, despite considering adding powerups, we ultimately decided against it. To increase strategy, we implemented a new rule where players could move their pieces in any combination that would add up to three spaces (as in, they could move their ghost two spaces and their pacman one, or vice versa) but would always have to move both pieces. This increased the strategy of the game and prevented players from leaving their ghost to guard their flag. 

##ITERATION 4 (FINAL)
Our major change in this iteration was to change where the players’ ghosts (now called lawyers) spawned and would respawn upon colliding with another. We changed these to be the unused corners on the opposite sides of the board. This ended up changing the game a lot and reducing stalemates and easy wins, though stalemates still occurred. We also decided that there needed to be more interaction between the two red pieces, so after some playtests and feedback we decided that a red piece that is attacked by the opponent’s red piece must be sent back to its original spawn point.

#SUPERPAC: A two player strategy about political intrigue!

##SETUP 
Set up the game as shown in the diagram below:
![Diagram]
(http://sophiecalhoun.com/images/superpacmandiagram.png)

##HOW TO PLAY
Each player has a target candidate (a non moving piece) on the opposite side of the board from their Superpacman piece. They also have a Lawyer piece on the adjacent corner of the board to their Superpacman. Players each have three moves each turn, and can split them how they want between their two pieces: for example, they could move their Lawyer two spots forward and their Superpacman one spot forward, or vice versa. All three moves must be used each term. Each player must attempt to reach their target candidate with their Superpacman, while defending their own candidate with their Lawyer piece. The players have multiple ways of defending their candidates. This can be accomplished by using their Lawyer piece to knock the opponent’s Superpacman back to their spawn point. When the two Lawyers collide, both must return to their respective spawn points. If Player 1 moves their Superpacman onto Player 2’s Superpacman, Player 2 must return their Superpacman to its spawn point. 





