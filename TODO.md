- Networked Animations
- Networked Effects
- Networked Projectiles
- Only send network update for physics entity on collision
	- Split into many types of `NetworkedLocation`events
		- one for players (networked playercontrol emulated on the clients nearby)
		- one for "simple" physics (props)
		- one for ai units (network ai state)
		- one for 
- Show ping and connection info for players
	- packet loss %
	- server tps
- Fix singleplayer
- Fix disconnect button
- fix the player collider

- Add a separate physics schedule that runs at a near fps rate
	- https://github.com/2143-Labs/bevy2025/pull/3
- add skills menu
- Add targeting menu
	- Add targeting cursors
		- Show last hit enemy for some skills
		- Tab target enemy
		- Tab target ally
		- Nearest ally/enemy
- Make items affect your movemnts and visible stats
- Make "Dead" component event work
- figure out how to have a component event on only client/server and not both
- Allow all units to be automatically networked
- make web version work
- 

https://i.devolved.us/pG2S.png


- Collision with projectiles
- enemies and enemy ai
- add stats system
- add skills
- fix going back to menu
- make client disconnect if the server times out





BEVY PICKING

TERRAIN SPAWN EXTRACT

SPAWN SECOND ZONE
}
p







ability to aim at cursor
ability to aim at point in front of you as cursor
ability to tab target stuff



