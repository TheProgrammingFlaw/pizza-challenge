# 🍕 Pizza Challenge - Frontend

This is the frontend implementation for the **Pizza Eating Challenge** app, which manages users, virtual currency, pizza purchases, and a leaderboard system built with React and TypeScript.

## 🚀 Features

- **User Management:** Create, update, delete, and manage players.
- **Pizza Logging:** Users can log pizzas only after purchasing them.
- **Leaderboard:** Displays players ranked by the number of pizzas eaten.
- **Real-Time Rank Updates:** Ensures the leaderboard reflects the latest data.

## 🛠️ Technology Stack

- **React.js**: Frontend framework for building the UI.
- **TypeScript**: A superset of JavaScript that adds type checking.
- **Axios**: For making HTTP requests to the backend API.
- **React Router**: For managing routes and navigation.
- **SocketIO**: For real-time updates.

## 📋 Setup Instructions

### Prerequisites

- Node.js (>= 14.x)
- npm (>= 6.x)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/TheProgrammingFlaw/pizza-challenge.git
   cd pizza-challenge
   ```

2. Install dependencies:

   Using npm:
   ```bash
   npm install
   ```

3. Start the development server:

   Using npm:
   ```bash
   npm start
   ```

   Visit `http://localhost:3000` to view the application.

## Features

- **Home Page**: The homepage provides buttons to:
  - Register a new user
  - View the leaderboard
  - Manage existing players

- **New User Registration**: Users can enter their name, age, and gender to register a new player. Upon registration, they are assigned a default balance of 500 coins.

- **Leaderboard**: Displays the real-time ranking of players based on the number of pizzas logged.

- **Manage Players**: 
  - View all players
  - Edit player information
  - Buy pizzas (using coins)
  - Log pizzas eaten
  - View transaction history for each player

## Deployment

The app is designed to be deployed on platforms like **Netlify**.

## 🏗️ Contributors

- [**TheProgrammingFlaw**](https://github.com/TheProgrammingFlaw)
