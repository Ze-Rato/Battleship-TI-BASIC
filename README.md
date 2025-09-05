## General Info
The game size (*NAVAL1* + *NAVAL2*) is approximately **1784 bytes** and It's writen in TI-BASIC. (**NOTE: This is the size on your calculator the file on other devices may varie**)

## Setting up the game
You can use TI Connect to send these program files to your graphic calculator. You should find *NAVAL1* and *NAVAL2* on programs. This was made on a ti-84 plus CE-T so it may not work in some calculators

## Playing the game
**PLACING THE BOATS:** *NAVAL1* is when the players select the spots they want their boats in. You control a "0" with the arrows and to place it you use ALPHA and the boat is ready, due to some more clean view I didn't use the while clear home method to uptdate the frames so it should run smoothly!

**ATTACKING:** When both players are done placing the boats you start the attacking phase, the *PLAYER1* will be the first to attack. On this phase you will see a table of colums and lines similar to the one you saw at the placing boats phase the only difference is that this table represents the shots you've already fired, for example if you hit a boat on 1A it will be displayed as "X" if you missed a shot on A2 it will be displayed "0". To shot you just need to press enter when you're done with looking into previous shots, after that a input will appear asking for colums(1-8) you fill it and press enter then other one asking for lin(A-G) will appear and after you fill and once again press enter you will be able to shot, to know if your shot was either *HITTED* or *WATER* you can look at the superior right corner. If you accidentally fill the column/line input with a character that triggers a syntax error, you can select "goto" or just click 2 when the syntax error appears, after which you can fill the input again. If you accidentally hit enter and want to look at the table again, you can use quit to exit the program and open *NAVAL2* to restart your turn with the table displayed again.
## Some Pictures

![Captura 2](https://user-images.githubusercontent.com/132148561/236564239-cdace80a-d5c9-4ce1-b94e-0c48c3b6beea.png) 
![Captura 3](https://user-images.githubusercontent.com/132148561/236564251-a57fac6c-4864-401c-8cb1-e3f0e085aff1.png) 
![Captura 4](https://user-images.githubusercontent.com/132148561/236564256-395ae562-3775-4119-a8dd-062bac7ff16f.png) 

## Upadtes and Patches

|    Version    | Date of Realease | Changes Description |
| ------------- | ------------------- | -------- |
| 1  | 05/05/2023 | -Launch and translation to English.   |
| 1.1 | 07/05/2023 | -Made the getKey command more efficient.   |
| 1.2 | 25/05/2023 | -Fixed the bug where the placed boats would visually disappear if you overlapped them with another boat|
| 1.3 | 01/06/2023 | -Added missing translations in *NAVAL2* <br> -Fixed an error on *Naval2* where C was used as constant and the collums variable <br> -Now if you shutdown/stop on the attacking phase it restarts on the player's turn where the game was interrupted (You need to execute *NAVAL2*)<br> -Improved performance by removing unecessary characters (for example the " on the end of an outoput)|
| 1.4 (Current) | 21/06/2023 | -Removed an useless variable on *NAVAL1* <br> -Deleted some unnecessary characters on *NAVAL1*|


## Final Notes
If you have any suggestions regarding otimization, issues and improving the game in general it would be much apreciated since I'm still a begginner.

If you want to reset a game you can run *NAVAL1* but if you want to 
continue a game you'll execute *NAVAL2* instead.

Also if you have other calculators models (TI 83, TI-NPIRE, etc) I would greatly appreciate your feedback!
