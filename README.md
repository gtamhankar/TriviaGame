# TriviaGame
ASSIGNMENT 5 - Trivia game using JavaScript for the logic and jQuery to manipulate HTML

Submitted On: 10/23/2018

Technologies: HTML & CSS & Bootstrap & jQuery

This is assignment 5: https://unc.bootcampcontent.com/UNC-Coding-Boot-Camp/UNCHILL201808FSF3/blob/master/homework/05-timers/homework-instructions.md

Inputs/Files: index.html, README.md 
Css folder: main.css,  uses bootstrap.css with web link
Images folder: grader.jpg

Outputs: Basic game page 

This is a simple version of trivia game - Are you smarter than a 5th Grader?.

Notes & Limitations:
--------------------
* Hardcoded globally - number of questions. But The trivia is coded in such a way that it will be easy to pass number of questions , 
  Question category and or time from front end. The Quizz is scalable to different levels of difficulty with ease.
  
Future Scope:
-------------
The trivia quizz question class has subject as a property. Hence the trivia can be scaled to different subjects.
Due to constraint of time, I have created a simple trivia game!

Logic:
1) Define and set global variables like number of questions, time, scores, Question bank. 
2) On page load, render random NON REPEATING array for question numbers for number of questions defined per quizz.
3) Disable the quizz - The quizz must be taken for the time duration assigned. Hence, we have a trigger to start the quizz so that the quizz is timed.
   The Quizz options and submit button is disabled until the start quizz is clicked.
4) "Start Quizz" enables the quizz and disables the start quizz option until the game is over (either timer or on submit) 
5) Once the game is over in step 4, show the score, get the percentage of the score, show appropriate msg and reload the game with random questions again.


Run Instructions:
--------------
To run localy:

1) Clone or download this git repository.
2) Run index.html in your web browser.
3) click on the "Quizzz Me" to start playing!

