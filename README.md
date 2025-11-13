# REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR

*COMPANY*:  CODTECH IT SOLUTIONS

*NAME*: SHAIK ABDULHAFEEZ

*INTERN ID*: CT06DR1513

*DOMAIN*: Full Stack Web Development
 
*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

#The Real-Time Collaborative Document Editor is a web-based project that allows multiple users to work on the same document at the same time. This means that when one user types, edits, or deletes something in the document, the same changes instantly appear on everyone else’s screen without needing to refresh the page. It works in real-time, just like popular tools such as Google Docs. The main goal of this project is to make teamwork and communication easier when editing text documents together online.

The project is built using modern web technologies like React.js for the frontend and Node.js with WebSocket or Socket.IO for the backend. The React part handles what users see on the screen, such as the text editor, buttons, and user interface. The Node.js server helps all connected users share their changes instantly. For example, if one user adds a sentence, the server immediately sends that update to everyone else who is viewing the same document.

Inside the project, the folder structure is clean and organized. The client folder holds all the files related to the frontend part of the application. It includes folders like public and src. The public folder contains static files such as index.html, images, icons, and other assets that help in displaying the web page properly. The manifest.json file helps in defining how the app should behave when installed as a web application, and the robots.txt file gives instructions to web crawlers.

The src folder contains the main React code. Important files here include App.js, which is the main component of the frontend, and index.js, which connects the React app to the HTML page. The CSS files (App.css and index.css) are used to style the web page, making it look nice and user-friendly. Other files like reportWebVitals.js and setupTests.js are part of React’s testing and performance setup.

On the backend side, the server.js file runs the Node.js server. This file plays a major role in handling real-time communication. It uses WebSocket or Socket.IO to create a connection between the users and the server. When a user edits something, the server catches that change and instantly sends it to all other connected clients. This two-way connection ensures smooth collaboration without delay.

The package.json files store the project’s dependencies — these are the packages and tools needed to run the app. For example, React, Socket.IO, Express, and other libraries might be listed there. The node_modules folder contains all these installed dependencies.

The main features of this project are:

Real-time editing: Any change made by one user appears instantly for all others.

Multiple users: Many users can edit the same document at once.

Synchronization: The data remains consistent among all users without conflicts.

User-friendly interface: Built using React for smooth and clean UI.

Live communication: Achieved using WebSocket or Socket.IO technology.

The Real-Time Collaborative Document Editor can be useful for students, teams, writers, or organizations that need to collaborate online. It removes the need to send files back and forth and allows everyone to stay on the same page. It demonstrates key concepts in modern web development such as real-time data handling, client-server communication, and responsive UI design.

In short, this project shows how technology can bring people together to work more efficiently. It’s a perfect example of how front-end and back-end systems can communicate to create a seamless, interactive experience.

#OUTPUT

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/55f75b7d-ba96-493b-b620-c0e3dbeab615" />
