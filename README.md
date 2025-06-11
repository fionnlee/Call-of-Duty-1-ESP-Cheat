# Call of Duty 1 ESP Cheat
Created a basic ESP cheat for Call of Duty 1.1 (2003) that shows player locations and simple visual info on screen.
```
0x18BC04 //Entity List between 0x448
0x14 // name
0x3A0 //X
0x3A4 //Y
0x3A8 //Z
0x3F0 //Pitch | Crosshaire
0x400 //isDead
0x34 //Team (0 = no team(everyone same DM) 1 = Defence 2 = Attack 3 = spec)

0x20715C //Local Player
0x2095A8 //viewMatrix
0x14 //LX
0x18 //LY
0x1C //LZ
0xC4 //Pitch

Exploit
0x1CBB0C //weapon 32
```

![Menu](https://github.com/fionnlee/Call-of-Duty-1-ESP-Cheat/blob/main/image/menu.png?raw=true)

# Note
<b>This cheat does not work in fullscreen mode. Use your preferred DLL injector to inject the cheat into the game.
Make sure to inject the DLL while connecting to a server.
This is a simple ESP cheat made just for fun — don’t take it too seriously.</b>
