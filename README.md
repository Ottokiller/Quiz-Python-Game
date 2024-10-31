# Quiz Game 
Welcome to the Quiz Game! This simple Python-based game challenges your knowledge with a series of fun questions, and it even tracks high scores to keep things competitive. Whether you're a trivia buff or just looking for a quick mental warm-up, this game is for you!

# Project Overview
The Quiz Game is designed to test players with five general-knowledge questions. At the end of the game, the player’s score is saved and compared with previous scores, creating a high score leaderboard. It’s a great way to practice Python fundamentals while having a bit of fun!

# Features 
Interactive Quiz: Players answer questions and receive immediate feedback on whether they were correct.
High Score Tracker: Stores top scores in a file and displays the leaderboard.
Case-Insensitive Answers: Makes sure that minor differences in capitalization don’t affect your answer.
Score Persistence: Saves scores in a text file (high_scores.txt), so scores persist even after the game is closed.

# Key Functions 
quiz_game(): Runs the main quiz, asking each question and tracking the player’s score.
read_high_scores(): Reads the list of high scores from high_scores.txt, creating the file if it doesn’t already exist.
save_high_score(): Saves a new score to the leaderboard, keeping only the top 5 scores.
main(): Coordinates the quiz and high score saving, running the game from start to finish.

# How to Play 
Run the Script: Start the program by running main().
Answer the Questions: Type in your answers as prompted.
Check Your Score: At the end of the game, see your final score and where it ranks on the leaderboard.
