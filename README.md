# Quizy - Online Quiz Platform

Welcome to **Quizy**, an online quiz platform designed to make learning and testing knowledge fun and interactive. This project allows users to create, share, and take quizzes on various topics.

## Features

- **User Authentication**: Secure login and registration system.
- **Quiz Creation**: Easily create quizzes with multiple-choice questions.
- **Quiz Sharing**: Share quizzes with others via a unique link.
- **Real-time Results**: Get instant feedback on quiz performance.
- **Leaderboard**: See how you rank against other users.

## Screenshots

![Home Page](screenshots/home.png)
![Quiz Page](screenshots/quiz.png)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/akshitsutharr/Quizy-Online-Quiz.git
    cd Quizy-Online-Quiz
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Set up the environment variables:
    ```sh
    cp .env.example .env
    ```
    Edit the `.env` file with your configuration.

4. Start the server:
    ```sh
    npm start
    ```

### Running Tests

To run tests, use the following command:
```sh
npm test
