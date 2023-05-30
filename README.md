 
(Established under the Presidency University Act, 2013 of the Karnataka Act 41 of 2013)
DEPARTMENT OF COMPUTER SCIENCE AND ENGINEERING 
CSE3150 FRONT END FULL STACK DEVELOPMENT

SUDOKU
Mini - Project Report

Submitted by
PRAMODH YADAV M      20201ISE0053

In partial fulfillment for the requirement of 6th Semester
CSE3150 Front End Full Stack Development

Under the Guidance of
Dr. P Sudha,
Assistant Professor (SG), Computer Science Department, Presidency University
Academic Year 2022 - 2023

Table of Contents

1.	Introduction	
1.1	Project resources link
1.2	Running project link

2.	Technologies Used

3.	Project Scope

4.	Project Objectives

5.	System Requirements

6.	Usage Guide

7.	Project structure

8.	Future Enhancement

9.	Conclusion


1.INTRODUCTION:
The Sudoku game is implemented using HTML, CSS, and JavaScript, the user-friendly interface of the game consists the puzzle board which is a 3x3 and 9x9 grid with some cells filled with numbers. The controls are located on the left side of the screen. They include a "New Game" button, which generates a new Sudoku puzzle when clicked, if you're having trouble, you can also use the "Solver" button to reveal the values of every cell.
1.1. PROJECT RESOURCES LINK: https://github.com/pramodhyadavm/sudoku 
1.2. RUNNING PROJECT LINK:
https://rawcdn.githack.com/pramodhyadavm/sudoku/16c62a5d28e65126ce0bee8e966706ede0608860/index.html

2. TECHNOLOGIES USED:
•	HTML
•	CSS
•	JAVASCRIPT
•	REACTJS
•	GIT
•	VS CODE (editor)

3. PROJECT SCOPE:
•	Sudoku grid with a predefined number of pre-filled cells.
•	Generated puzzles have a unique solution.
•	Allow users to input numbers into empty cells and validate their inputs.
•	Highlight conflicting entries in the grid to help users identify mistakes.
•	Provide options to check the correctness of the entire grid or a specific row, column, or 3x3 box.
•	Timer to track the duration of the game.
•	Display a congratulatory message upon solving the puzzle successfully.
•	An intuitive and visually appealing user interface for the Sudoku game.
•	JavaScript functions to generate Sudoku puzzles with varying difficulty levels.
•	Algorithms for checking the correctness of user inputs and highlighting conflicts.
•	Functions to handle user interactions, such as filling in cells, checking solutions, and resetting the game.
•	Timer using JavaScript's Date object or a timer library.
•	Multiple difficulty levels (e.g., easy, medium, hard) for generated Sudoku puzzles.
•	Adjust the number of pre-filled cells based on the chosen difficulty level.
•	Ensure generated puzzles are solvable and adhere to the selected difficulty.

4. PROJECT OBJECTIVES:
•	fully functional Sudoku game using HTML, CSS, and JavaScript.
•	interactive user interface that allows users to easily input numbers and navigate through the game.
•	Sudoku grid with 9x9 cells and initial puzzle configurations.
•	validation mechanism to check the correctness of the user's input at any given time.
•	visual feedback to the user, highlighting incorrect entries or indicating when the puzzle is completed successfully.
•	features such as hints or suggestions to assist users in solving the puzzle.
•	timer to track the user's progress and provide an additional challenge.
•	Offer multiple difficulty levels (easy, medium, hard) to cater to players with varying skill levels.
•	Incorporate a scoring system to keep track of the user's performance and encourage improvement.
•	"solve" function that allows users to view the solution if they get stuck or want to check their answers.
•	Provide options for users to save their progress and resume the game later.
•	sound effects or visual animations to enhance the user experience and make the game more engaging.

5.SYSTEM REQUIREMENTS:
Hardware Requirements:
•	Computer with a minimum of 2 GHz processor.
•	At least 2 GB of RAM (4 GB or higher recommended) for smooth performance.
•	Sufficient hard disk space to store the project files and dependencies.

Software Requirements:
•	Text editor or Integrated Development Environment (IDE) to write code. Some popular choices include Visual Studio Code, Sublime Text, or Atom.
•	Web browser (latest version) for testing and running the game. Recommended browsers include Google Chrome, Mozilla Firefox, or Safari.

Programming Languages and Libraries:
•	HTML: Ensure that you have a basic understanding of HTML markup language for creating the structure of the web page.
•	CSS: Familiarity with CSS (Cascading Style Sheets) is necessary to style and format the game elements.
•	JavaScript: Proficiency in JavaScript programming language is required for implementing the game logic, user interaction, and functionality.

Internet Connectivity:
•	An internet connection is not mandatory for developing or running the Sudoku game locally on your computer. However, you may require internet access to download dependencies or resources during the development process.

6. USAGE GUIDE:
•	Objective:
The objective of Sudoku is to fill a 9x9 grid with numbers from 1 to 9, such that each column, each row, and each of the nine 3x3 sub grids (also known as boxes or regions) contains all of the digits from 1 to 9 without repetition.

•	Grid Layout:
The Sudoku grid consists of a 9x9 square divided into nine 3x3 sub grids. Each cell in the grid can contain a number from 1 to 9 or can be left blank.

•	Starting Grid:
A Sudoku puzzle usually starts with some cells pre-filled with numbers. These pre-filled numbers provide initial clues to solve the puzzle.

•	Rules:
Each row must contain all numbers from 1 to 9 without repetition.
Each column must contain all numbers from 1 to 9 without repetition.
Each 3x3 sub grid must contain all numbers from 1 to 9 without repetition.

•	Gameplay:
Start by analyzing the provided clues and the grid to identify any numbers that can be directly placed based on the rules.
Begin with the easiest clues and work your way to more complex deductions.
Use logic and elimination to determine the possible values for each empty cell.

7. PROJECT STRUCTURE:
User Interface:
•	Graphical user interface (GUI) for the Sudoku game.
•	Include a grid to display the Sudoku board and allow the user to interact with it.
•	Buttons for solving the puzzle, checking the solution, resetting the board, etc.

Sudoku Board Representation:
•	Data structure to represent the Sudoku board.
•	Two-dimensional array or a matrix to store the numbers in the Sudoku grid.
•	Functions to initialize the board, set and get values in cells, and check for valid moves.

Input and Validation:
•	Allow the user to input values into the Sudoku board through the GUI.
•	Validate the input to ensure it meets the Sudoku rules (e.g., numbers 1-9 in each row, column, and box).
•	Display error messages if the input is invalid.

Solving Algorithm:
•	Algorithm to solve the Sudoku puzzle.

Game Logic:
•	Solving algorithm with the game logic.
•	Request hints or solve the puzzle automatically.
•	Provide options to check the current solution, show errors, and validate the complete board.

Game Controls:
•	functionality for buttons and controls in the GUI.
•	Handle user interactions such as clicking cells, entering numbers, and using game controls.
•	Update the Sudoku board and the GUI based on user actions.

8. FUTURE ENHANCEMENT:
•	We are trying to implement timer to solve the sudoku puzzle and, 
•	Implement number of clicks done during solving puzzle using ReactJS

9.CONCLUSION:
In conclusion, the Sudoku game project has been successfully developed, implementing all the necessary features and functionalities of a traditional Sudoku game. The project involved designing an intuitive user interface, generating Sudoku puzzles with varying levels of difficulty, and implementing game logic to ensure accurate gameplay.
Throughout the project, careful attention was given to usability and user experience, resulting in a user-friendly interface that allows players to easily interact with the game and enjoy the Sudoku-solving experience. The generated puzzles offer a challenging and enjoyable gameplay experience for users of all skill levels.
