

```markdown
# Trello Clone

A full-stack Trello-style task management application built as a university capstone project. The goal was to apply agile development practices while working with a relational database, MVVM architecture, and secure user authentication.

![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-Java-6DB33F?logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?logo=mysql&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue)

## Features

- User authentication (sign up / log in)
- Create and manage workspaces
- Collaborate with other users
- Create, track, search, and filter tasks

## Tech Stack

| Layer       | Technology                          |
|-------------|-------------------------------------|
| Architecture| MVVM                                |
| Frontend    | React, HTML, CSS, JavaScript        |
| Backend     | Java, Spring Boot                   |
| Database    | MySQL                               |

## Project Structure

```
trello-clone/
├── frontend/          # React application
└── backend/           # Spring Boot application
```

> Adjust the folder names above if your actual directory structure differs.

## Frontend

### Prerequisites

- Node.js 16.15.0
- npm 8.5.5
- An IDE with JavaScript/Node support (VS Code or IntelliJ recommended)

### Setup

```bash
cd frontend   # or your actual frontend folder name
npm install
npm install react-router-dom@5.2.0
npm install @material-ui/core
npm install react-datepicker --save
```

### Running

```bash
npm start
```

The app runs at [http://localhost:3000](http://localhost:3000).  
**Important:** Keep the frontend on port 3000 — the backend is configured to accept API calls from this origin.

## Backend

### Prerequisites

- JDK 17
- Maven 3.8.4
- An IDE with Java support (VS Code or IntelliJ recommended)
- VPN access to the Dalhousie network (required to reach the hosted database)

### Setup

1. Open the backend project in your IDE.
2. Ensure the project is configured to use **JDK 17** and **Maven 3.8.4**.

### Running

Locate and run the main class:

```
TrelloCloneApplication.java
```

The Spring Boot application will start and connect to the MySQL database (VPN required).

## Getting Started (Full Stack)

1. Connect to the Dalhousie VPN.
2. Start the backend (`TrelloCloneApplication.java`).
3. Start the frontend (`npm start`).
4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Screenshots

<!-- Add screenshots here once available -->
<!-- Example:
![Login Page](docs/screenshots/login.png)
![Board View](docs/screenshots/board.png)
-->

## Future Improvements

- Add drag-and-drop for cards
- Real-time collaboration (WebSockets)
- File attachments
- Dark mode
- Mobile responsiveness improvements


