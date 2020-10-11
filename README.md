# TetrisGame using Gestures

Usually to play any game on a computer we use sevaral keys to control the game. Example left,right,up and down arrows or W,A,s,z.

In this project I developed a gesture controlling Tetris game using open source library for Computer Vision that is OpenCv. When you start running the program it opens your camera and searches for a Blue object. This object acts as a game controller.
By holding a Blue object in your hand you can move the falling blocks right, left ,down ,rotate. These are the 4 keys which I mapped to windows keyboard based on the location of the blue controlling block. I divided the screen into 5 parts one for each key and a neutral space where it does nothing (kind of resting place).

The program works for windows machines, if you have MacOS you need to change directkeys.py.
