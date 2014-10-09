=== Plugin Name ===
AA Audio Player



Tags:aa , player , mp3 , 
Requires at least:4.0
Tested up to:4.0
Stable tag:aaaudioplayer
License: GPL
Contributors :A and A
==Description==
To add the music player
[aplayer src='defealt mp3 src']

To start a playlist 
[startaap]


add a music to playlist 
[addpl src='http://.../example.mp3' name='Example Song 1']
[addpl src='http://.../example2.mp3' name='Example Song 2']


End of a playlist
[stopaap]



An example code 
---------------------------------

Player
[aplayer src='http://.../example.mp3']

Playlist 
[startaap]
[addpl src='http://.../example.mp3' name='Example Song 1']
[addpl src='http://.../example2.mp3' name='Example Song 2']
[stopaap]