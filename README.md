# Alpha-Beta Chess AI

## Honor Code Violation Disclaimer:                                                
This is work done as an assignment for Dartmouth College's CS76.                   
If you are currently enrolled at Dartmouth college and will ever take this course, **downloading, using, modifying, running, or even looking at this code is an honor code violation.** Please don't; it is not for you.
                                                                                   
If you are a professor teaching this course and wish for me to take down the REPO, shoot me an email at carter.bastian1@gmail.com, and I'll be happy to do so. 

# Description and Instructions
Instructions for Use From Command Line (Mac OSX):

Before running any of the code, add Chesspresso-lib.jar to your classpath with 
the following command (from the root directory of the project):
    sudo cp Chesspresso-lib.jar /Library/Java/Extensions/

    And then enter your password.

To run the default build of the code, simply type the following command:
    make

To Change the Test Case:
  1. Go to ChessClient.java line 63 and surf through the available set ups
  2. Comment the test case you don't want
  3. Uncomment the test case you do want
  4. Run the make utility from the command line (enter "make")

To Change Which AI is Being Tested (or to play against the AI):
  1. Go to ChessClient.java line 117 and browse the MoveMaker set ups
  2. Comment the set-up you don't want
  3. Uncomment the set-up you do want
  4. Run the make utility from the command line (enter "make")

Note that in all of the test case set ups, black is the stronger AI and thus
should win.


Description of Custom Files:
  AlphaBetaAI.java  -   A file implementing Alpha-Beta search with iterative 
                        deepening and a sophisticated utility function

  BadEvalAI.java    -   A file implementing Alpha-Beta search with iterative
                        deepening and a simplistic (flawed) utility function

  MinimaxAI.java    -   A file implementing Minimax search with iterative
                        deepening and a sophisticated utility function
