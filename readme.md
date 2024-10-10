# Note Taker

## Description

The **Express Note Taker** is a simple web application that allows users to create, save, and delete notes. It's built using Express.js for the back-end and allows users to manage their notes seamlessly with an intuitive interface. This app can be handy for users who want to jot down tasks, thoughts, or reminders and keep track of them efficiently.

### Motivation

The primary motivation for building this project was to simplify note-taking by providing a user-friendly application that stores notes persistently. This project allowed me to explore RESTful API development using Express.js, working with file systems, and handling client-server interactions.

### Problem Solved

This app solves the issue of managing notes across multiple platforms by storing them centrally on a server. Users can access their notes anytime, ensuring they don’t lose track of important tasks.

### What I Learned

Through this project, I learned:
- How to create a RESTful API using Express.js
- Managing data storage with the file system in Node.js
- Creating dynamic web interfaces with client-side JavaScript
- Handling HTTP requests and responses effectively

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Features](#features)
- [How to Contribute](#how-to-contribute)
- [Tests](#tests)

## Installation

To run this application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/emangelic/note-taker.git

2. Navigate to the project directory:
    cd note-taker

3. Install the necessary dependencies:
    npm install

4. Start the server:
    node server.js

5. Open your browser and navigate to http://localhost:3001 to start using the app.

## Usage
Once the app is running, users can:

Write and save new notes.
View previously saved notes on the left sidebar.
Delete notes they no longer need.
To add a new note:

Enter the title and body text of your note, then click the "Save" button.
To delete a note:

Click the trash icon next to the note in the sidebar.

## Credits
This project was built using the following resources:

 - Express.js Documentation
 - Node.js
 - Bootstrap for styling
 - Icon provided by FontAwesome
 - Javascript
 - HTML
 - CSS


## License
This project is licensed under the MIT License. For more details, see the LICENSE file.

## Features
- Create, save, and delete notes
- Persistent note storage using local files
- Clean and simple user interface
- RESTful API for note management

## Tests
To run tests, use the following command:

 - bash
 - Copy code
 - npm test