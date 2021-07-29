Doodle Champion Island Games
=============================

This is an offline backup copy of the Doodle Champion Island Games by Google and Studio 4°C.
The game has been modified to forcefully load the english text and force fullscreen, as well as some other minor improvements
like turning off smoothing on Gecko-based browsers (and forcing moz-opaque), as well as fixing an issue with web browsers not supporting the Web Audio API.

Preferably you should play the game on google.com but if for some reasons it is blocked
or you wish not to be tracked (note that for now, the submitscore url is still used and it still loads the leaderboard from Google's servers, that may change later),
you can do so here :

https://gameblabla.github.io/doodle-champion-island-games-Google/

I would like to thank @potherca-blog for some of his interesting changes :P


Playing the game offline
=========================


Firefox
=======
You can just open the index.html (you may have to change a setting for that though if reads from file:// are not allowed).

Chrominum and forks (Brave)
======================================
Yyou will need to host your own HTTP server.
Run :
python3 -m http.server

in a terminal and load up the game at 127.0.0.1:8000.


COPYRIGHT
=========

Of course the game code itself belong to their respective owners, Google and Studio 4°C Co., Ltd.

I would recommend that you do not host this on your website or elsewhere without Google's permission.
The only purpose of this project is to be able to run this game offline in case the game gets shut down.
