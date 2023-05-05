Download Link: https://assignmentchef.com/product/solved-cse271-project2-knowledge-of-guis-and-problem-solving
<br>
For the second project, you will be combining your knowledge of GUIs and problem solving. In addition, there is a bonus aspect that will be your first foray into Artificial Intelligence.   Like the other project, the TAs nor I will provide no assistance on implementation of the project, rather you can and should ask us concept questions only, which we will be happy to answer. The exception to this is the bonus aspect described below, which we can work through and help you design.  You will note that the requirements are stated in the voice of a non-technical customer. Thus, you must make many design and implementation choices, which we will then put on our “technical hats” to grade.

Gui

In class, we went over the n-Queens problem.  Implement a GUI representing an 8×8 chessboard.  Allow users to click on a space on the chessboard to place a Queen with the Mouse. For partial points, you can simply place the letter “Q”, or for full points, you can place an image of your choice, learning the SWING API for images on your own. If a user clicks on a space that already has a Queen, that Queen is removed.  They can place up to 8 Queens total. (10 points)

AT ANY TIME a user can click a button to determine if their (partial) solution is correct thus far.  So, for example, if I have 3 Queens placed, I can click that button to find out if those 3 Queens are “safe” at this point and that this is a valid partial solution.   This means that you will have to transform the current (visual) state of the board into something your program can understand. If the Queen placement puts Queens at risk, you must identify the conflict visually on the board AND textually in your GUI.  You are free to use (and modify) any of the code we did together in class/from the textbook to assess your potential solution, or come up with your own. Just CITE IT! (10 points)

Points will be given for the look and feel of your GUI, efficiency of your code (for example, does it make sense to calculate all the partial solutions up front or evaluate the currently proposed solution only/each time the button is pushed), and following the conventions and rules we discussed in class. (5 points)

Artificial Intelligence

For these points, you will be extending your project utilizing artificial intelligence.

Basic

Have a button on your GUI called “Tip” that can be pressed ONLY when there are less than 8 Queens on the board.  You may hide or disable this button if there are 8 or more queens on the board.  If this button is

pressed, you will highlight or indicate in text OR the GUI a suggestion for where the user should place their next Queen.  For these 5 points, simply pick one of the spaces on the board that meets the current constraints of the board, that is, puts the Queen in a “Safe Space”.

Bonus

For FULL bonus points, have a separate button on your GUI called “Smart Tip” that can be pressed ONLY when there are less than 8 Queens on the board, and is disabled or invisible otherwise. This button will pick the next Queen location based on the largest number of solutions that will still be an option after placing that new Queen by looking at all acceptable and relevant solutions to the 8 Queens problem. This full bonus part is the only part of the project you can ask for direct help on from me and the TAs.  Of course, we can give you indirect help on everything else.

Presentation

You will be giving a 3-minute presentation to your lab section of your solution.  You must describe

<ol>

 <li>All your design/programming decisions, (2 points)</li>

 <li>Any challenges you faced, (2 points)</li>

 <li>What you learned, (2 points)</li>

 <li>Any interesting features your project has. (2 points)</li>

</ol>

(2 points) Will be given for adhering to the time constraints and overall presentation.

INCLUDE YOUR PRESENTATION file (ppt, pptx, pdf) in your Canvas submission, separate from your ZIP, so it can be loaded quickly during class.  You will lose 2 points if you neglect to do this, no exceptions.

You will not be loading your code and running your programs (there is not enough time). So, you should do screen captures, animations, or movies to showcase (showoff) your game and support your points.

<h2>Tips</h2>

Some students have trouble, especially on MACs, with component background colours.  You can try playing with <u><a href="https://docs.oracle.com/javase/7/docs/api/javax/swing/JComponent.html#setOpaque(boolean)">setOpaque (API link here)</a></u> and seeing if it works better. You will not be docked if the background color looks weird unless it affects the alternating colors of the board, which it should not.

A friendly reminder, that the root directory of your Java projects is the Project (level) folder and not the src folder.  Any file paths you use will have to keep that in mind. For example, if you tried to load an image “jedi.png” it would look at the project level for that image. Avoid using absolute paths that rely on directory names. Rather, use relative paths.

At no point in your final submission should you be putting things to the console (System.out).  Now that you know GUI development, you must present all information on your GUI.