# Campusly

A friendly campus organizer starter project for a first semester engineering student. It brings class tasks, deadlines, campus events, and an attendance calculator into one place.

## Run it

1. Open `index.html` in a recent web browser. No install is needed.
2. Choose Student, Admin, or Student incharge; enter any valid email and a password with at least 6 characters.
3. Try adding a task, ticking it complete, opening the calendar, or calculating attendance.
4. In Admin or Student incharge view, post a task or event and review the sample attendance request. Use the profile at the bottom of the sidebar to sign out.

The project uses plain HTML, CSS, and JavaScript so you can learn the building blocks before adding a framework. Demo data is saved in your browser's local storage. Use the same browser on the same device to see it again. To reset the demo, clear this site's local storage.

## What works in this demo

- Login page with Student, Admin, and Student incharge role choices
- Student and staff dashboard views (demo sign-in, not secure authentication)
- Task and submission list with due dates, completion toggles, and optional source links
- Monthly calendar showing task deadlines and events
- Campus event list and teacher/admin event posting
- Attendance percentage calculator and suggested 75% target
- Simulated student verification request and admin approve/decline controls
- Responsive layout for desktop and mobile screens

## Before real students use it

This is a front-end prototype. The login form only demonstrates role selection and does not verify passwords or secure accounts. It does not send email or SMS, sync data between students and teachers, or verify attendance against college records. Those features need a server, a database, secure accounts, and email/SMS provider credentials. Do not use the demo for private student information. A sensible next step is to learn basic JavaScript, then build a small backend and connect it to a database; notifications can be added after due dates and user contact details are stored securely.

## Files

- `index.html` — page structure and app screens
- `styles.css` — colors, layout, and responsive styling
- `app.js` — demo data and interactions
- `login.css` — login page styling
