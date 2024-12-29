# Stock Station

A full-stack stock trading application built using the MERN stack (MongoDB, Express, React, Node.js) with features like user registration, stock price fetching, buying/selling stocks, and transaction history.

---

## Features

- **User Registration and Login**: Secure user authentication using hashed passwords.
- **Stock Price Fetching**: Real-time stock price updates using NSE India API.
- **Trading System**: Users can buy and sell stocks based on current prices.
- **Transaction History**: Displays a detailed transaction history for each user.
- **Insights**: Displays the latest business-related news using a third-party API.

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/purneshsv/mern-stock-platform.git
   cd mern-stock-platform

## Install Dependencies:

npm install

## Set up MongoDB:
	•	Update the MongoDB connection string in conn.js:

mongoose.connect("your-mongodb-connection-string", {
  useNewUrlParser: true,
  useUnifiedTopology: true,
});

## Start the Server:

npm run dev

## Access the Application:
	•	Open your browser and navigate to:

http://localhost:3000

## Project Structure

- **`server.js`**: Main server file defining routes and logic.
- **`conn.js`**: MongoDB connection setup.
- **`register.js`**: Defines Mongoose schemas for users, transactions, and holdings.
- **`stock.js`**: Fetches real-time stock details using NSE India API.
- **`views/`**: Contains EJS templates for rendering dynamic HTML pages.
- **`public/`**: Static files (e.g., CSS, images).
- **`package.json`**: Manages project dependencies and metadata.

## Dependencies

The project uses the following Node.js packages:

- **Express**: Web framework for Node.js.
- **Mongoose**: MongoDB object modeling tool.
- **EJS**: Template engine for rendering dynamic HTML.
- **Body-Parser**: Middleware for parsing incoming request bodies.
- **BcryptJS**: For hashing passwords.
- **Axios**: For making HTTP requests to APIs.
- **Nodemon**: Automatically restarts the server during development.
- **Stock-NSE-India**: For fetching stock data.
  

---
## Install dependencies using:

npm install

## Usage

### User Features

- **Register**: Create an account with details like name, email, password, and phone number.
- **Login**: Access your account securely.
- **Buy Stocks**: Purchase stocks using virtual altcoins.
- **View Transactions**: See a history of all transactions.


## API Endpoints

### GET Endpoints

- `/`: Render the registration page.
- `/login`: Render the login page.
- `/index`: Render the main dashboard after login.
- `/aboutus`: Display information about the platform.
- `/insights`: Show the latest business news.

### POST Endpoints

- `/register`: Register a new user.
- `/index`: Fetch stock price details and render on the dashboard.
- `/buy`: Handle stock purchase transactions.
 
