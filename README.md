Natural Selection 2 Bot
=============

The goal is to get an ai controlled player running in NS2, that mimics human players as much as possible :)


Changelog
------------

* Version 0.5
	Fixed to work with NS2 build 229
	Changed pathfinding to use BotGorge's BotAIPathMixin by ZycaR
	Several small improvements
	
* Version 0.4
	Improved fighting skills
	Marine: Added automatic power node / player repairing
	Marine: Added automatic alert triggering (medpack, ammo, orders)
	Skulk: Fixed destroyed power node attacking issue 

* Version 0.3
	Added automatic bot count adjusting
	Added infantry portal building

* Version 0.2
	Added random walking
	Fixed some auto targeting issues
	Fixed some aming issues
	Improved automatic weapon selection

* Version 0.1
	Added basic alien support
	Added auto attacking
	Added random environment observing 

* Version 0.0
	A simple marine bot that uses the pathfinding system and builds unbuilt structures

Installation
-----------

	Copy the .lua files to your Steam/steamapps/common/natural selection 2/ns2/lua directory :)


Usage
-----

Ingame, open the console and "addbot n" to add n bots or "setbots n" to add/remove bots to have n active ones