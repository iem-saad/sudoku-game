# sudoku-game
# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Clone the repo

* Go into sudoku-game directory and run `chmod +x game.sh` `chmod +x menu.sh` `chmod +x welcome.sh`

* Run `./game.sh`

* That's all you need to do, `dpkg` will automatically install all required packages like `figlet` and game will be up and running 👍 ⭐

                                                         ABOUT APP
As a student of FAST-NUCES i was assiged a mid project to create a sudoku game using shell scripting, keeping in mind the code computation time and DRY approach.
So, i created this game by using simple logics. I created different files and included them in one diver file which is `game.sh`. The game has 2 modes, EASY and Dificult. In EASY mode i display a sudoku board of 3X3 matrix and in Difficult Mode i display a board of 9X9. On a right move the played index will be represented by green color and on wrong move with a red color. I've used `figlet` & `tput` packages to make UI of game look better.
Regarding logic of game, To avoid deadlock. I create a unique solution of SUDOKU game everytime game is played by using a pre exisiting sudoku solution which i 've stored in the game. The logic is easy and you can easily understand it as the code is wel;l formatted and properly commented.
* If you have any query you can freely ask me at iem.saad@hotmail.com I will feel happy to help you. ♥️
