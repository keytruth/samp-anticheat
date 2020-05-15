# samp-anticheat

(This system contains code snippets that have been made publicly available)  
A simple anti-cheat system for your SA-MP server.

### Callback
Use the following callback for actions when suspicious cheats are detected:

```
playerid - ID of the player who is suspected of using cheats.
code - the cheat code that the player is suspected of using. (You can view the codes below)
```
```pawn
public OnPlayerCheat(playerid, const code)
{
    Kick(playerid); // Example action
    return 1;
}
```

### Codes anti-cheat:
```
1 - Teleport
2 - Speed Hack
3 - Slapper (invalid name)
4 - Health Hack
5 - Armour Hack
6 - Money Hack
7 - High Ping
8 - Weapon&Ammo Hack
9 - Invisible Hack
10 - Parkour Mod
11 - CJ-Run
12 - Slapper
13 - Silent Aimbot
14 - Pro Aimbot
15 - Tele-Kill (Custom)
```
