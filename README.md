# SteamServerDiscordTracker 
 A Simple Discord Bot That Allows You to Get Updates about players on Steam Servers Using Valve Server Protocol
 
 # Setup
 Simply install requirments, fill out the config with your discord bot key, channel, and server you would like to watch then run main.py
 
 # Commands
.getPlayerCount returns how many players that are connected to the server

.addEnemy(string) accepts a string, adds them to the database and tracks when they are on the server

.removeEnemy(string) accepts a string, removes enemy from database and stops tracking them

.enemys returns list of enemys currently being tracked

.checkEnemys returns all the enemys currently connected to the server
