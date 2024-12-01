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
- npm (>= 6.x) or yarn

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

   Or using yarn:
   ```bash
   yarn install
   ```

3. Set up environment variables:
   
   Create a `.env` file at the root of the project and add the necessary environment variables for Firebase, API URLs, and other configurations.

   Example `.env`:
   ```plaintext
   REACT_APP_FIREBASE_API_KEY=your-firebase-api-key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your-firebase-auth-domain
   REACT_APP_FIREBASE_PROJECT_ID=your-firebase-project-id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your-firebase-storage-bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-firebase-sender-id
   REACT_APP_FIREBASE_APP_ID=your-firebase-app-id
   ```

4. Start the development server:

   Using npm:
   ```bash
   npm start
   ```

   Or using yarn:
   ```bash
   yarn start
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
