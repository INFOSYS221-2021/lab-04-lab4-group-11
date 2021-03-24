# Lab-04
Group 11: Steven Cao - scao962 Renee Braddock - rbra390 Henry Chen - jche955 Malachi Blair - mbla240

Exercise One:
1. List three data types used in this program.
 integer, string, boolean

2. List any value variables or reference variables in this program.
  value variable: letter, dupeBoard, move, possibleMoves, playerLetter
  reference Variable: **copy** = getBoardCopy(board) 
  

3. Give an example of a sequence in this program.

print('Welcome to Tic Tac Toe!')
 
while True:
 '# Reset the board
 theBoard = [' '] * 10
 playerLetter, computerLetter = inputPlayerLetter()
 turn = whoGoesFirst()
 print('The ' + turn + ' will go first.')
 gameIsPlaying = True

4. Give an example of a condition in this program.
Line 89 (if isSpaceFree(board, i):...)

5. Give an example of an iteration in this program.
Line88 (for i in movesList:....)

6. Give an example of a list or collection in this program. What is saved in the list / collection?


7. Give an example of a function that has at least one parameter in this program. And, briefly explain what the function is trying to achieve.


8. How does the program determine who wins the game? List the functions that the program use to determine the winner.


9. If the code on line 165 is changed from break to gameIsPlaying = False, will this change the behaviour of the program?


11. What does while True: do in this program?
