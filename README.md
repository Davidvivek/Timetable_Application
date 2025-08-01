My Timetable App
A sleek, real-time web application designed to help Computer Science & Engineering students at ISM Dhanbad keep track of their class schedule. 
Built with a modern tech stack, this app provides a clean, user-friendly interface to view upcoming classes and browse the entire timetable with ease.

url: https://schedule-sync-cse-s3.netlify.app/

✨ Features
This application comes packed with a variety of features to make managing your class schedule simple and efficient:
Dynamic Timetable Display: The app intelligently shows you the very next class you have, whether it's later today or on a future day.
Weekend Mode: On Saturdays and Sundays, the app displays a motivational quote to help you relax and recharge for the week ahead.

Multiple Viewing Options:
View by Day: Browse the full schedule for any day of the week.
View by Subject: Select a specific subject to see all its scheduled classes throughout the week.

User Authentication: Utilizes Firebase's anonymous authentication to provide a personalized experience without requiring users to create an account with a password.

Visitor Logging & Analytics:
Securely logs every user's first visit.
Tracks the total number of logins and the timestamp of the last visit for every user, providing valuable analytics.

Permanent Dark Mode: The UI is locked in a developer-friendly dark theme. A theme-toggle button is included, 
which humorously informs the user that light mode is "forbidden" for CSE students.
Logout Functionality: A simple and clear logout button allows users to end their session and return to the welcome screen.
Fully Responsive: The layout is designed to work beautifully on desktops, tablets, and mobile devices.

💻 Tech Stack
This project was built using a modern, lightweight tech stack focused on performance and ease of development:

Frontend:
HTML5
Tailwind CSS: For utility-first styling and a clean, responsive design.
JavaScript (ES6 Modules): For all the client-side logic and interactivity.

Backend & Database:
Firebase: Used as the Backend-as-a-Service (BaaS) platform.
Firebase Authentication: To handle seamless and secure anonymous user sessions.
Cloud Firestore: As the NoSQL database to store user profiles and visitor logs in real-time.

Deployment:
Netlify: The application is deployed live via Netlify, connected directly to a GitHub repository for continuous deployment.

🚀 How to Use
Upon visiting the website for the first time, you will be greeted with a welcome model.

Enter your full name to log in.
The main dashboard will then load, showing you the next upcoming class.
You can use the "View by Day" or "View by Subject" buttons to explore the rest of the timetable.
Click the logout button in the header to end your session.
