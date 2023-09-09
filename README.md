# OIBSIP-Online-EXamination

This project creates a simple online examination program with a graphical user interface (GUI). Let's break it down step by step:


1- Package and Creator Comments:

* The code starts with a comment that mentions the package name (onlineexamination) and the creator's name (Laxman Singh Negi).

  
2- Import Statements:

* The code imports various classes from the Java Swing library (javax.swing) for creating the GUI.


3- Class Definitions:

* login and OnlineTestBegin are two classes defined in the code.
  

4- login class:

* This class extends the JFrame class and implements the ActionListener interface. This means it creates a window for the user to log in.

* It contains components like labels, text fields, and a submit button.

* When the submit button is clicked, it checks for a valid password. If the password is not entered, it prompts the user to do so.



5- OnlineTestBegin class:

* This class also extends the JFrame class and implements the ActionListener interface. It represents the main window for the online test.

* It includes labels, radio buttons, "Next" and "Skip" buttons, and a timer.

* The questions and options are set based on the current question number. The user can select an option and proceed to the next question.

* The timer counts down from 10 minutes, and if time runs out, it displays "Time Out".

* The user can also review questions and check their score at the end.



6- Constructor and Components:

* In both classes, there are constructors where various components like labels, buttons, text fields, etc., are initialized and added to the GUI.7Action Listeners:

* Both classes have methods to handle actions (button clicks). When a button is clicked, the program responds accordingly.


7- Method Definitions:

* set(): This method sets the question and options based on the current question number.

* check(): This method checks if the user's answer is correct based on the current question.

8- Main Method:

* The main method is in the OnlineExamination class.

* It creates an instance of the login class, sets its size, and makes it visible. This is how the program starts.

9- Exception Handling:

* There is a try-catch block that catches any exceptions and displays an error message dialog if an exception occurs.


  
=> Overall, this code creates a simple GUI-based online examination program where users can log in, take a multiple-choice test, and receive a score at the end. The test has a time limit, and users can skip questions and review them later.







