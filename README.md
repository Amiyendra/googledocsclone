Google Docs Clone

This is a simple Google Docs clone application built using Node.js, Express.js, Quill.js, and Socket.io. This application allows multiple users to collaboratively edit a document in real-time, similar to the functionality provided by Google Docs.

Features
Real-time collaborative document editing.
Text formatting using the Quill.js rich text editor.
User presence indicator.
Document version history.
User-specific cursors.
Technologies Used
Node.js: Backend server environment.
Express.js: Web application framework for Node.js.
Quill.js: Rich text editor for text formatting.
Socket.io: Library for real-time communication.
HTML/CSS: Frontend structure and styling.
MongoDB: Database for storing document versions (optional feature).
Getting Started
Clone the repository:
bash

cd google-docs-clone
Install dependencies:
bash
Copy code
npm install
Start the server:
bash
Copy code
node server.js
Open your web browser and navigate to http://localhost:3000 to access the application.
Usage
Create a new document by clicking the "New Document" button on the homepage.

Share the document URL with collaborators.

As users join the document, their cursors will appear, and you can see their presence in the user list.

Start typing to see real-time changes and updates from other users.

Use the Quill.js toolbar to format text with bold, italics, bullet points, etc.

The document's version history can be accessed to see changes over time.

Folder Structure
public/: Contains static assets such as CSS, JavaScript, and images.
views/: Contains the HTML templates for rendering the application pages.
server.js: Main server file where the Express.js app is set up and Socket.io is configured.
routes/: Contains route handlers

