Arcade-game
===========

This argade-game can be run on your desktop (if you get all files from repo in github). At starting game, there is one player charactor('cat girl') and there are several enemies('bugs') on screen. Each bug has random speed and moves left to right. You can control position of player by using key(left, right, up, down). The goal of this game is that player must deliver each cat depending on colors  of top of screen without collision with bugs. If your player is located on top of screen with your cat, the game is reset.


Control method(user)
--------------------
- Just pressing key ('up, down, left, right')


Code architecture(developer)
----------------------------
- resources.js:
This is simply an image loading utility. It eases the process of loading image files so that they can be used within this game.

- engine.js:
This file provides the game loop functionality (update entities and render), draws the initial game board on the screen, and then calls the update and render methods on player and enemy objects (defined in app.js).

- app.js:
This file includes constructors and several functions of Enemey and Player. There are functions to render images, update speed rate and positions for each enemy(enemies are push into allEnemeis array). There are also functions to render images, update positions by pressing key for player.


Installation & Play
-------------------

Install and play Arcade-game :

    - download zip file from repo on github (below)
    - https://github.com/Younghun-Jung/frontend-nanodegree-classic-game
    - open index.html on your web browser.


Support
-------

If you are having issues, please let me know.
We have a mailing list located at: youngj6169@gmail.com


License
-------

The project is licensed under the Udacity frontend-Nanodegree course
