# BomberGame-Compiled
Intro: 
------------
The compiled project ready to use version of a small network game reminding a bit of the old bomberman.

Requirements:
------------
Require Java to be installed (Build with Java version 8).

Most likely only works on windows

Server and Client: 
------------
There is 2 files (Game server and Game client) and a folder with the images. The path for the images is hardcoded for windows and need to be in the correct folder.

The Server needs to be run first, it will control the map and informations about the game, like the score and player placement. When it is run, it will first let your choose the map/level you wish to play on, then it will give you the IP address and the lokal address that is used by the client to find the correct server.

The client can then be run multiple times, or from multiple computers. You will need to type in either the IP address or choose use localhost. Then choose your Player name and the player will enter the game.

Score: 
------------
* Moving gives 1 point 
* Shooting cost 10 points 
* Killing a player steals 33% of their points 
