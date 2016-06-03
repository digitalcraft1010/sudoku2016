Readme.txt

1) Since this is the first time I try Sudoku (yes that's right, I am more of a DOOM kinda guy, sorry); I have to first figure out the game rule and how an individual would play the game.

2) It is tested on Chrome(Mac/Win/Android), Firefox(Max/Win), Safari(MaxOS), and IE9(Vista).

3) I've also learned that there is a good number of sudoku code available out there thus I do refer to them for inspiration for solution validating.

4) Since it is a tabulated gameboard, I have decided to use the <table> tag that is rendered proportional to screen width for optimal user experience. There is no SEO concern and minimal accessibility concern.

5) Each input field is restricted to a one digit number with the spinner feature turned off to avoid confusion and error.

6) Input is restricted to values between 1 to 9, invalid entries will be ignored and the field will return to blank.

7) Validation of input and solution for the puzzle is carried out on every key-up. This will eliminate redundant user interaction like "Enter" or "Submit".

8) Once the puzzle is solved, a modal will pop-up to notify the user. The modal is semi-transparent and the background is left scrollable so as to allow the user to view the finished puzzle. Clicking on the modal will start a new game. This could be further imporved to allow for:
	a) a modal that can be closed without erasing the puzzle / restarting the game.
	b) load a new puzzle from a pre-defined list of puzzles.
	c) allow for printing of the solved puzzle.
	d) showing time taken to solve the puzzle.

9) A 'hidden' feature is built into the sample solution image below the puzzle. Once the sample solution is clicked, the puzzle will be solved. This is more for my own use for testing the program.

10) A live version of the puzzle can be access from http://www.8dstudio.com/sudoku2016/


Norman Choo
2016-06-03