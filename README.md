# quizzify
Interactive Quiz Platform – A fully responsive web application offering multiple  quiz categories with real-time countdown timer, instant score calculation, and  comprehensive answer review system. Built with HTML, CSS, and JavaScript.

Resolved formatting approach for seamless content copyingQuiz Application
A fully responsive web application offering multiple quiz categories with real-time countdown timer, instant score calculation, and comprehensive answer review system. Built with HTML, CSS, and JavaScript.
Features
 Multiple Quiz Categories

General Knowledge
Science
History

 Real-time Countdown Timer

15 seconds per question
Visual warning when time is running low
Auto-submit on timeout

 Score Tracking & Analytics

Live progress bar
Percentage-based scoring
Performance-based feedback messages

 Answer Review System

Detailed review of all answers
Highlights correct vs. incorrect responses
Shows correct answers for missed questions

 Keyboard Navigation

Press 1-4 to select answers
Press Enter to proceed to next question
Tab & Space for accessibility

 Fully Responsive Design

Optimized for desktop, tablet, and mobile
Dark theme UI for reduced eye strain
Smooth transitions and animations

Tech Stack

HTML5 – Semantic markup and structure
CSS3 – Responsive layout with flexbox
JavaScript (Vanilla) – Core logic and interactivity



Open in browser:

# Simply open index.html in your browser
open index.html
Or use a local server:
python -m http.server 8000
# Visit http://localhost:8000
How to Play

Select Category – Choose from General Knowledge, Science, or History
Start Quiz – Click "Start Quiz" to begin
Answer Questions – Select your answer (or press 1-4 on keyboard)
Beat the Timer – Answer within 15 seconds per question
Review Results – See your score and detailed answer breakdown
Try Again – Restart with a new randomized quiz

Keyboard Shortcuts
KeyAction1-4Select answer optionEnterProceed to next questionSpaceActivate focused buttonTabNavigate between elements
Project Structure
quiz-app/
├── index.html       # Main HTML file with all screens
├── styles.css       # Responsive styling and theme
├── script.js        # Quiz logic and interactivity
└── README.md        # Documentation
Screens
Start Screen

Category selection dropdown
Quiz introduction
Start button

Quiz Screen

Question display
Multiple choice options (A, B, C, D)
Countdown timer with color warning
Progress bar
Next button (appears after answer selection)

Result Screen

Final score with percentage
Performance-based emoji feedback
Detailed answer review
Restart button

Features Breakdown
Dynamic Question Bank

5 questions per category
Questions are shuffled randomly for each quiz
Easy to add new categories and questions

Timer System

15-second countdown per question
Color changes to red when ≤5 seconds
Auto-advances on timeout with penalty

Accessibility

ARIA labels for screen readers
Keyboard navigation support
High contrast dark theme
Tab-friendly button navigation

Feedback System

Visual highlighting of correct/wrong answers
Score-based performance messages:

80%+ :  Excellent!"
50-79% :  Good effort!"
<50% :  Keep studying!"



Future Enhancements

Add difficulty levels (Easy, Medium, Hard)
Implement leaderboard system
Save progress to localStorage
Add more categories (Geography, Sports, etc.)
Dark/Light mode toggle
Export results as PDF
Multiplayer quiz mode
Timed practice sessions
Question shuffle within category

Browser Support

Chrome (latest)
Firefox (latest)
Safari (latest)
Edge (latest)
Mobile browsers (iOS Safari, Chrome Mobile)

Performance

Lightweight (~15KB total)
No external dependencies
Fast load time
Optimized animations

Author
Divyansh Verma
GitHub: @divyansh-verma


Made with love for learning
