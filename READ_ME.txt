Web Based Game Server with the following features/constraints.


GAME : 
	(1)  On the home page players should be able to start a game or join current games.
	(2)  When joining a game, ask for player name.
	(3)  Each player is assigned a random color, when he/she joins the game.
	(4)  A board of configurable dimension will be shown to all the players.
	(5)  A game automatically starts when at least 2 players join it.
	(6)  Each player can hover over the board and squares will light up with their assigned color.
	(7)  Player can select the square by clicking it.
	(8)  A player can acquire the square by clicking it.
	(9)  Once a square is acquired it gets filled with the player's color.
	(10) An acquired square cannot be taken by any other player and its color will not change on hovering.
	(11) Once a square is selected by a player, all players are blocked for x seconds to do anything.
	(12) After x seconds, board becomes available again for all the players.
	(13) Game ends when all squares are colored and players with maximum squared colored wins.
	
	
CLIENT SIDE :
			HTML, CSS, Java Script, JQuery.
			Socket.io for real time Game.


SERVER SIDE :
			Node JS.
			Socket.io for real time Game.

			
RUN APPLICATION :
				npm install.
				node main.js.
				
				
APPLICATION DESCRIPTION : 
						(1)  Players should be able to start a game or join current games.
						(2)  Each player is assigned a random color, when he/she joins the game.
						(3)  A game automatically starts when at least 2 players join it.
						(4)  A player can acquire the square by clicking it.
						(5)  Once a square is acquired it gets filled with the player's color.
						(6)  Players with maximum squared colored wins.
