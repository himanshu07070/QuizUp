# QuizUp

Creating a program that will read in a quiz provided via a `CSV` file and will then give the quiz to a user keeping track of how many questions they
get right and how many they get incorrect. Regardless of whether the answer is correct or wrong the next question should be asked immediately 
afterwards.

The CSV file will be in a format like below, where the first column is a question and the second column in the same row is the answer to that 
question.

`5+5,10`

`7+3,10`

`1+1,2`

`8+3,11`

`1+2,3`

`8+6,14`

`3+1,4`

`1+4,5`

`5+1,6`

`2+3,5`

`3+3,6`

`2+4,6`

`5+2,7`

At the end of the quiz the program will output the total number of questions correct and how many questions there were in total. 
Questions given invalid answers will be considered incorrect.

We added a timer and the default time limit will be 30 seconds, but should also be customizable via a flag. This quiz will stop as soon as the time 
limit has exceeded. That is, it  will not wait for the user to answer one final questions but should ideally stop the quiz entirely even if you are 
currently waiting on an answer from the end user.

Users will be asked to press enter (or some other key) before the timer starts, and then the questions will be printed out to the screen one at a
time until the user provides an answer. Regardless of whether the answer is correct or wrong the next question should be asked.
