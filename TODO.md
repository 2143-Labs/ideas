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

https://i.devolved.us/pG2S.png
