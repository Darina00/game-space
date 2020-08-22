# Game "Space"

The rules are quite simple: with **short presses of the spacebar**, the astronaut on the rocket manages to stay in the air and not hit the surface. And you also need to guide the astronaut through all the obstacles in the form of asteroids. This game is endless, a point is awarded for each obstacle passed.

***************

`The app is divided into 5 parts:`
* Folder _audio_ - is intended for storing audio files
* Folder _css_ - is intended for storing cascading style sheets
* Folder _img_ - is intended for storing pictures of which the game itself consists
* Folder _js_ - a lot of JS files which we will discuss in more detail below
* File _index.html_ - the main layout of the game itself

***************

`The files that are stored in the JS folder:`

File name         | File content
------------------|-----------------------------------------------------------------------
alert.js          | Modal window function, reload the main window and redraw the game
audio.js          | Initializing sound files
button.js         | Event when clicking the "Play" button
checkScore.js     | Checking for adding an account
checkTouch.js     | Checking the astronaut for touching obstacles and stopping the game
drawAsteroids.js  | Drawing of obstacles in the form of asteroids, generation of obstacles
drawBackground.js | Drawing the background
drawCosmonaut.js  | Drawing of an astronaut
drawFrontground.js| Rendering the foreground
gameLogic.js      | Basic game logic
keydown.js        | Function that is triggered when you press the spacebar (astronaut take off)
objects.js        | All constants and variables of all objects

**[Go to game](https://darina00.github.io/game-space/)**

