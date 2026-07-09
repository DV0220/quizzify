Quizzify

Interactive Quiz Platform – A fully responsive web application offering multiple quiz categories with a real-time countdown timer, instant score calculation, and a detailed answer review system. Built with HTML, CSS, and JavaScript.

Features


Multiple quiz categories (General Knowledge, Science, History) with 5 questions each
Questions shuffled randomly on every quiz attempt
15-second countdown timer per question, turns red when 5 seconds or less remain
Auto-advance with the question marked wrong if the timer runs out
Progress bar that updates as you move through the quiz
Real-time score tracking with percentage-based result
Instant answer feedback — correct answer highlighted in green, wrong pick highlighted in red
Detailed answer review after the quiz, showing your answer vs. the correct one for every question
Keyboard shortcuts (1–4 to select an answer, Enter to move to the next question, Space/Enter to activate a focused option)
Fully responsive, dark-themed UI


Tech Stack


HTML5
CSS3 (Flexbox-based responsive layout)
JavaScript (Vanilla ES6)


Project Structure

Quizzify/
│── index.html
│── styles.css
│── script.js
│── README.md

How to Run


Clone the repository

git clone https://github.com/divyansh-verma/quizzify.git
cd quizzify


Open the project folder.
Open index.html directly in your browser, or serve it locally:


python -m http.server 8000

Then visit http://localhost:8000

How to Play


On the start screen, choose a category — General Knowledge, Science, or History
Click Start Quiz to begin
Select an answer by clicking an option or pressing 1–4 on your keyboard
Answer within 15 seconds — the timer turns red in the last 5 seconds
Click Next Question (or press Enter) to continue
After the last question, view your score, a performance message, and a full answer review
Click Try Again to return to the start screen and take another quiz


Keyboard Shortcuts

KeyAction1–4Select the corresponding answer optionEnterSelect a focused option, or proceed to the next questionSpaceSelect a focused answer option

Screens


Start Screen – Category dropdown (General Knowledge / Science / History) and a Start Quiz button
Quiz Screen – Question counter, live countdown timer, progress bar, four answer choices, and a Next/See Results button
Result Screen – Score with percentage, performance message, full answer-by-answer review, and a Try Again button


Features Breakdown


Question Bank – 5 hardcoded questions per category, reshuffled at the start of every quiz
Timer System – 15-second countdown per question; text turns red at 5 seconds or below; auto-submits as an incorrect/timed-out answer if time runs out
Scoring – Score is calculated as a percentage of correct answers out of total questions
Feedback Messages

80% and above: "Excellent! You really know your stuff." 
50–79%: "Good effort! A bit more practice and you'll ace it." 
Below 50%: "Keep studying — you'll get there!" 



Answer Review – Lists every question with your chosen answer, and shows the correct answer as well whenever you got it wrong


Browser Support


Chrome, Firefox, Safari, Edge (latest versions)
Mobile browsers (iOS Safari, Chrome Mobile)


Future Improvements


Difficulty levels (Easy, Medium, Hard)
Leaderboard system
Save progress/scores with localStorage
More categories (Geography, Sports, etc.)
Randomized questions pulled from an external API
Dark/Light mode toggle


Author
Divyansh Verma
GitHub: https://github.com/DV0220
