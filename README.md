Mouse and Keyboard Activity Tracker
This is a simple web application designed to track mouse and keyboard activity in a web browser. It logs the idle time of the user and displays it in the console.

Usage
Clone or download the repository to your local machine.
Open the index.html file in a web browser.
Open the browser console to view the idle time tracking.
Features
Tracks mouse movement and clicks.
Tracks keyboard key presses.
Calculates idle time based on the last activity.
Logs idle time in the browser console.
How It Works
The application uses JavaScript to listen for mouse and keyboard events. It records the timestamp of the last activity and calculates the idle time by comparing it with the current time. If the idle time exceeds a threshold (set to 5 minutes or 300,000 milliseconds in this case), it logs the idle time in the console.

File Structure
index.html: HTML file containing the structure of the web page and the JavaScript code for activity tracking.
README.md: This file, providing information about the project.
LICENSE: License information for the project.
Dependencies
This project does not have any external dependencies.



Author
[abid]


