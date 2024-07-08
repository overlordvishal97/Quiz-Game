# Quiz-Game
This is a simple quiz game that asks the user a series of true or false questions. The game keeps track of the user's score and displays it at the end of the game.

# Classes

# Question_Model
The Question class models a single question. It has the following attributes:
text: The text of the question.
answer: The correct answer to the question.

# Quiz_Brain
The QuizBrain class models the quiz game. It has the following methods:

__init__: Initializes the quiz game with a list of questions.
still_has_questions: Checks if there are still questions left to ask.
next_question: Asks the next question in the list and checks the user's answer.
check_answer: Checks if the user's answer is correct and updates the score.

# Usage
To play the quiz game, simply run the main.py file. You will be asked a series of true or false questions, and your score will be displayed at the end of the game.

# Note
This is a basic implementation of a quiz game and can be extended to include more features and functionality, such as adding more question types or allowing users to add their own questions.

# Data
The quiz game uses a list of questions stored in the question_data variable in the data.py file. Each question is a dictionary with a question key for the text of the question and a correct_answer key for the correct answer. You can add or modify questions by editing this file.
