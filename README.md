# Pong

## Description
This is a simple pong game created using the Lua scripting and LOVE 2D game framework.
The game will keep track of the scores of the players and declare a winner after one player reaches a score of 10. The game has two modes, 'play' and 'practice'. At launch, press 1 for 'Play' mode or 2 for 'Practice' mode.

## Play Mode
Play mode allows the game to played user vs. user. Player 1 uses the 'W' & 'S' keys to move the paddle on the left side of the screen. Player 2 uses the 'Up' and 'Down' keys to control the paddle on the right. First to score 10 points is the winner. A point is scored by getting the ball past your opponents paddle and into their 'goal'.

## Practice Mode
Practice allows a user to play against the computer. The user can use either the 'W'/'S' or 'Up'/'Down' keys to move the paddle on the right. The paddle on the left is controlled by the computer and will move automatically to return the ball. First to score 10 points wins.

## Screenshots
![start_screen](images\screenshot1.JPG)
![gameplay](images\screenshot2.JPG)

## Prerequisites
-[Lua](http://www.lua.org/download.html)
-[LOVE2D](https://love2d.org/#download)

## Installation
1. Fork repositroy
2. Clone repository to your machine using terminal and 'git clone (URL)'
3. Install/download Lua and LOVE2D
4. Start improving your pong skills!

## Notes
Running the Lua with LOVE2D can be a bit tricky if you are not experienced with LOVE2D games. LOVE2D requires you give it a folder to open and run; meaning you cannot give it simply a file, like main.lua. The main.lua file must be contained within a folder. In the case of this project, the folder you would give to LOVE2D is the 'PONG-FINAL' folder which contains all the Lua files.

The easiest way to run the script is have two file explorers windows open; one with the LOVE2D folder open and the other with the folder containing your Lua script files. Click and drag the Lua folder onto the LOVE2D.exe icon/file. This will open and run the script using LOVE2D.

The other option is to create a new System Path Variable for LOVE2D. Create new path variable for the path to your LOVE2D folder (ex. C:\Program Files\LOVE). Once the path variable is set up correctly, you simply use the 'love .' command with the command prompt to open and run the script you are currently at. Or 'love (path your Lua folder) if you are not currently located at the project folder in your command prompt.

I built this project on Windows machine using VS Code so usuage may vary if you're using a Mac or Linux machine or a different IDE. LOVE2D suggests using editors such as ZeroBrane Studio or Sublime Text for ease as those editors allow you to launch LOVE2D games within them. So you're struggling to get the game running, you can try a different editor!

## Support
If you have issues or suggestions, please email me at samueldmaus@gmail.com