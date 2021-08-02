# Multiple-Choice-Quiz

I) In order to run the applet properly, you need to download the java classes above and follow the steps:

1) Open your terminal (or cmd).
2) Go to the path of your classes' file. (cd \path "on windows").
3) Compile your java files (use the command " javac *.java ").
4) Run your java program (main class wich is Quiz.java).
5) Done

II) Now, in order to add to or to change the questions of the quiz, follow:

go to the main class (Quiz.java) there is an array of objects called "qObj" represented :

           quiz2 [] qObj = {

            new quiz2("Question 1","op1","op2","op3","op4","op1","hint 1"),
            
            new quiz2("Question 2","op1","op2","op3","op4","op4","hint 2"),
            
            new quiz2("Question 3","op1","op2","op3","op4","op3","hint 3"),
            
            new quiz2("Question 4","op1","op2","op3","op4","op2","hint 4")
            
            };

- Put your questions on the "Question 1,2.." attribute(s).
- p1 , p2 , p3 , p4 are the choices.
- the 6th attribute is the correct answer (so, put the correct answer of the question there).
- hint 1 , hint 2 ... are the hints of the correct answers.

If you want to add other questions, all you have to do is: create a new object from the class quiz2 and add it to the array "qObj" :
       
            new quiz2("Your question","Option 1","Option 2","Option 3","Option 4","Correct answer","Hint"); 

III) The timing : if you want to give the player more time to answer the quiestions there is a int variable called time in the main class :
            
            int time = 60 // time by seconds
            
you can change it to whatever you want.
