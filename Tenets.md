

### Gameplay

1. This game is an Action RPG
	1. The game is played in real-time, not turn based.
	2. Items are randomly generated.
	3. These items allow you to access new content and areas.
	4. Areas are randomly generated
2. The game is a hardcore extraction shooter
	1. The game contains "Hostile Areas" which players can enter (called a "Raid")
	2. These Hostile Areas contain loot and sometimes other players
	3. Death in a Hostile Area is permanent, and items are dropped on death
	4. A "Stash," "Bank," or "Secure Container" can be used to store loot between Raids
3. Permanent progression is limited
	1. Each death should revert your character to the "default"/"level 1" state.
	2. Player power is purely gained on a per-character basis.
4. Item trading is allowed under an austrian free market
	1. Items, trading, and drops are server-authoritative.
	2. Goods in the economy may only be traded for goods or services from the same economy.
	3. No real money trading. No cross league trading.
	4. Scamming or deceiving other players is allowed, and players are encouraged to be vigilant and protect themselves.
	5. No single players death or loss is ever rolled back. Rollbacks may only occur on a whole-server basis
	6. Direct catallactic intervention is never performed . Instead, item scarcity and economics should be approached through game balance instead.
5. Networking 
	1. Botting is not allowed.
	2. Only one client may connect per computer.
6. Music
	1. Music is based on what the player is currently experiencing. 

### Programming
1. The number of systems using `World` should be minimized and annotated if required. `&mut World` is disallowed EXCEPT in the network
2. Packets should be sent using the `ServerNetworkingResources` and `ClientNetworkingResources` objects. Packets should always be received via the `UDPacketEvent`
	1. Packets in both directions should usually be forwarded to a local `MessageWriter` for further processing (eg `UDPacketEvent<T>` receives, then forwards messages to `MessageWriter<T>`, which is then processed in a second function by a `MessageReader<T>`))






base types

Staffs 2 handed magic thing
Wands 1 handed magic thing
Bows 2 handed magic thing
Pistol 1 handed ranged thing
AR 2 handed ranged thing
Swords 1/2 handed
Shield 1/2 handed



