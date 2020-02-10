//======================= Dave Revolution =========================//

Editors

Name : Michael Peretz
Id : 311597660

Name : Meir Vizan
Id :  302860788


The project is a game called Dave Revolution 
the porpase of game is the player must reach the door 
and for open the door he need to collect a key
and on the way he collision with a Enemy And Crow
and for continue he can to shoot the enemy and he can collect coin 
and when he have get a door with a key he pass to second level ...





============== Design =============

We have many class of management game 
Like:

Controller:
He manage all operation in a game the
responsible for all the movment of Dynamic object in game,
and Time game and header of game

Sound Manager:
  he responsible of all the sound in game
Collision Handling: 
 he responsible of all collision in the game
Board:   
he responsible of all change in objects game




Object :

	Static Object  derived from object:
		All this class derived from Static Object :

		Wall  :
		wall object in game
		
		Fake Wall  :
		fake wall he blockes the player fom reaching the key
		and player can destroy him by bullet
 
		Movement Bocker :
		Blocker enemy when they move

		Water  :
		Kind of mine

		Door  :
		Door object 

		Check Point  :
		When player reach to check point he save the position of player
		and if player will diad he return from the last checkpoint he visited

		Spiket :
		Kind of mine
		
		Consumable derived from Static Object:
			All this class derived from Consumable :

			Coin derived from Consumable  :
			When player reach them he get a point 

			Ammo derived from Consumable :
			When player get ammo get can shoot 			

			Life derived from Consumable  :
			get Life

			Door Key derived from Consumable  :
			Key object the player need to get a key for open door 
			

	Dynamic Object derived from object:
		All this class derived from Dynamic Object:
		
		Player  :
		Player Object himself he can move right and left
		 and bend over and jump and shooting

		Enemy  :
		he can move right and left
			
		Elevator:
		move right left

		Bullet:
		move by he get direction of player

		Crow:
		move right and left




Camera:
class he responsible view of the game

  
Info Bar
this class responsible of game header ,
include score of player and bullet number ,and time ,and life


Main Menu:
this class responsible on the menu when we star the game


Time Utils:
responsible of time levels


Animation:
responsible of all animation in a game


Animation Manager:
managerment of Animation


Level Loader:
read level from tmx file


 
========================== Data Structurs =============================

Vector<Unique_Ptr>  DynamicObject
Vector<Unique_Ptr> StaticObject

map for Design Paterns Multi Methods

map for level


==========================Design Patterns =============================

Multi Methods for collision

Fuctory for get object from level



===========================GitHub================================
GitHub : https://github.com/mikeper030/DaveRevolution
