# OIBSIP_Task_4

TASK_4:  ONLINE_EXAMINATION_SYSTEM BY SHRUTI_GODSE

The project should be capable of the following functionalities.

1)Login 2)Update Profile and Password 3)Selecting answers for MCQs 4)Timer and auto submit 5)Closing session and  6)Logout

EXPLANATION OF CODE: 

his Java program represents a simple online examination system with basic functionalities. Let's go through the code to understand its structure and functionality:

OnlineExam Class =>

This class encapsulates the online exam system.

It has fields for username, password, login status, time remaining for the exam, question count, user answers, and correct answers.
The constructor initializes the username, password, login status, exam time, question count, and arrays for user and correct answers. Correct answers are randomly generated (0 or 1) for each question.

The login method prompts the user to enter a username and password, verifies the credentials, and sets the login status accordingly.

The logout method logs out the user by setting the login status to false.

The startExam method allows the user to answer questions. It displays questions, collects user answers, and gives the option to submit manually or auto-submit after a certain time.

The submitExam method calculates the user's score based on correct answers, prints the score, logs out the user, and wishes them luck.

Main Method =>

The main method in the OnlineExam class is the entry point of the program.
It prompts the user to enter a username and password, creates an instance of the OnlineExam class, logs in the user, and starts the exam.

Exam Flow =>

Users are prompted to log in with a username and password.
After successful login, users can start the exam, where they answer multiple-choice questions (options are hardcoded as "Option 1" and "Option 2").
Users have the option to manually submit their answers or auto-submit when the time is up.

Random Correct Answers =>

The program initializes correct answers randomly (0 or 1) for each question. This is a basic way to simulate correct answers.

Auto-Submit Feature =>

The program attempts to simulate an auto-submit feature by using the Thread.sleep method to wait for a certain time (in this case, the remaining exam time multiplied by 10 seconds).
If the sleep is interrupted (e.g., the user manually submits the exam), it proceeds to submit the exam.

Note =>

The timeRemaining field is set to 10 minutes for the sake of simplicity. Adjustments can be made based on actual exam requirements.
The program uses a simple scoring mechanism, giving one point for each correct answer.

Overall, the code represents a basic online examination system with login, exam-taking, and scoring functionalities.

OUTPUT:-

PS C:\Users\Shruti\Desktop\c&c++> javac OnlineExam.java

PS C:\Users\Shruti\Desktop\c&c++> java OnlineExam

Enter your username and password

ShrutiGodse

shruti123

Sucessfully You are registered!  :)

Log in to give the Exam 

Username: ShrutiGodse

Password: shruti123

Login successful Best of Luck Dear

You have 10 minutes to complete the exam.

Question 1:
1. Option 1
   
2. Option 2
   
Your answer (1 or 2): 1

Question 2:

1. Option 1
   
2. Option 2
   
Your answer (1 or 2): 2

Question 3:

1. Option 1
   
2. Option 2
   
Your answer (1 or 2): 2

Question 4:

1. Option 1
   
2. Option 2
   
Your answer (1 or 2): 1

Question 5:

1. Option 1
   
2. Option 2
   
Your answer (1 or 2): 1

Question 6:

1. Option 1
   
2. Option 2
   
Your answer (1 or 2): 2

Question 7:

1. Option 1

2. Option 2
   
Your answer (1 or 2): 1

Question 8:

1. Option 1
   
2. Option 2
   
Your answer (1 or 2): 2

Question 9:

1. Option 1
   
2. Option 2
   
Your answer (1 or 2): 2

Question 10:

1. Option 1
 
2. Option 2
   
Your answer (1 or 2): 2

Would you like to submit?

1:Yes

2:NO

1
Your score is 1 out of 10.

Best of luck :)

Logout successful.

PS C:\Users\Shruti\Desktop\c&c++>







