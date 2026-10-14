# QueueCare — Clinic Queue Management System

A responsive clinic-focused queue management demo using HTML, CSS, JavaScript, Node.js and Express.

## Run locally
1. Install Node.js.
2. Open this folder in VS Code.
3. Run `npm install`.
4. Run `npm start`.
5. Visit http://localhost:3000.

## Pages
- `/` home
- `/token.html` patient token creation and department selection
- `/queue.html` queue overview
- `/admin.html` staff queue controls
- `/display.html` counter display

## Deploy
Push to GitHub, then create a Render Web Service using build command `npm install` and start command `npm start`. Leave Root Directory blank.

## Demo limitations
Queue data is stored in memory and clears when the server restarts. Staff controls are not password-protected. No database, authentication, audit log, or clinic-grade privacy controls are included. Do not use with real patient data until these protections are implemented. Public queue views show patient names; use token-only displays in production.
