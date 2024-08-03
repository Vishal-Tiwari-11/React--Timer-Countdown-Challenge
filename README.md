Timer Counter Challenge (Game)
Description
The Timer Counter Challenge is a fun and engaging game built using React. The game consists of various timer challenges where players must stop the timer as close to the target time as possible. This project showcases the use of React hooks for state management, a component-based architecture, and efficient user interaction handling.

Features
Multiple Challenges: The game offers four different levels of difficulty:
Easy (1 second)
Not Easy (5 seconds)
Getting Tough (10 seconds)
Pros Only (15 seconds)
Dynamic Timer: Players can start, stop, and reset the timer for each challenge.
Result Modal: A modal window that displays the result when the timer stops or the time runs out.
User Feedback: Visual cues and messages to inform players about the current state of the timer (active or inactive).
Components Overview
App Component: The main component that renders the player interface and the timer challenges. It orchestrates the overall layout of the application.
TimerChallenge Component: Handles the logic and display for individual timer challenges. Manages the timer state, handles user interactions, and updates the user interface accordingly.
ResultModal Component: Displays the results to the player once the timer stops or reaches zero. It shows the target time, the result, and provides an option to reset the challenge.

Installation
To run this project locally, follow these steps:

Clone the repository:

git clone https://github.com/yourusername/timer-counter-challenge.git
cd timer-counter-challenge

Install dependencies:

npm install

Start the application:

npm start

This will start the application on http://localhost:3000, where you can access it in your web browser.

Usage
Navigate to the Application: Open your browser and go to http://localhost:3000.
Select a Challenge: Choose one of the four available challenges based on your preferred difficulty level.
Start the Timer: Click the "Start Challenge" button to start the timer.
Stop the Timer: Try to stop the timer as close to the target time as possible by clicking the "Stop Challenge" button.
View Results: The Result Modal will display your performance. You can reset the challenge and try again.
