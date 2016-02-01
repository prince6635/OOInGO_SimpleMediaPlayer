# Object Oriented in GO: Simple Media Player

```
$ go run mplayer.go
Enter following commands to control the player:
lib list -- View the existing music lib
lib add <name><artist><source><type> -- Add a music to the music lib
lib remove <name> -- Remove the specified music from the lib
play <name> -- Play the specified music
Enter command-> lib add HugeStone MJ ~/MusicLib/hs.mp3 MP3
Enter command-> play HugeStone
Playing MP3 music ~/MusicLib/hs.mp3
..........
Finished playing ~/MusicLib/hs.mp3
Enter command-> lib list
1 : HugeStone MJ ~/MusicLib/hs.mp3 MP3
Enter command-> lib view
Enter command-> q
```
