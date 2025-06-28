INTELLECT QUEST - A Console-Based Quiz Game in C

Features:

Console-based quiz interface
Three topics: Ramayana, Mahabharata, and General Knowledge
Each topic has 50+ questions stored in arrays
Random selection of questions for each session
30-second timer per question (simulated)
Scoring system and performance feedback

How It Works:

The user is prompted to enter their full name.
Instructions are displayed explaining how the quiz works.
The user selects a topic and difficulty level.
The program randomly selects 10 questions from the chosen topic.
For each question, four options are displayed.
The user inputs their answer within 30 seconds.
The score is calculated and a message is shown based on performance.

Score Feedback:

0 to 3: You can do better!!
4 to 7: You performed well !!
8 to 10: Excellent performance !!

Files:

quiz.c (main source code file)

How to Compile:
Use any C compiler (e.g., GCC)

Command to compile:
gcc quiz.c -o quiz

Command to run:
./quiz

Libraries Used:

stdio.h (for input/output)

stdlib.h (for random number generation)

time.h (for timing and random seed)

Author:
Tirth Patel
