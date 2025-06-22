Visitor Management System
A simple, modern, and responsive Visitor Management System powered by Google Sheets for easy, serverless deployment.

Features
Visitor Check-In: Collects details such as Name, Email, Phone, Company, Purpose, and Host Person.
Today's Visitors List: Shows the list of visitors checked in today, with a check-out button.
Google Sheets Backend: All data is stored and managed in Google Sheets via Google Apps Script.
No Backend Server Needed: All logic is handled in the browser and by Google Apps Script.
Modern UI: Built with Tailwind CSS and Font Awesome for icons.
Success Modal: Shows an immediate feedback modal on check-in.
Check-Out Functionality: Allows checking out a visitor instantly.
How It Works
Check-In: Visitor enters their details and submits the form.
Data Sync: Details are sent to a Google Apps Script Web App, which writes the data to a Google Sheet.
Visitor List: The page fetches "today's" visitors from the sheet and displays them in a table.
Check-Out: Clicking "Check Out" sends a request to update the visitor's status in the sheet.
Deployment
Prerequisites
A Google account
A Google Sheet (create one for your visitor log)
Access to Google Apps Script (script.google.com)
1. Create & Deploy the Google Apps Script
Open Google Apps Script.
Create a new project.
Paste the following sample code (modify as needed for your sheet structure):
