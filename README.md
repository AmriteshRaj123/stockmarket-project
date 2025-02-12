Real-Time Stock Market App (MERN + Socket.io)

📌 Overview

The Real-Time Stock Market App is a web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with Socket.io for real-time stock price updates. Users can search for stocks, track live prices, and maintain a watchlist.

🚀 Features

🔐 User Authentication (JWT/Firebase) – Secure login & signup

📈 Real-Time Stock Prices using Socket.io & Finnhub API

🔎 Search & Watchlist – Save stocks for easy tracking

📊 Stock Chart Visualization – View historical trends

📰 Market News & Insights – Get stock-related news

🚨 Price Alerts (Optional: Web push/email notifications)

🛠 Tech Stack

# Frontend:

React.js (Vite)

Tailwind CSS / Material UI

Socket.io-client (for real-time updates)

Axios (for API calls)

Recharts / Chart.js (for stock charts)

# Backend:

Node.js + Express.js

Socket.io (WebSockets for live updates)

MongoDB + Mongoose (Database for watchlist & users)

Finnhub / Alpha Vantage API (Stock market data)

JSON Web Token (JWT) for authentication

# Deployment:

Frontend: Vercel

Backend: Render / Railway

Database: MongoDB Atlas


📂 Folder Structure

# real-time-stock-market/
│── backend/           
│   ├── models/       
│   ├── routes/       
│   ├── server.js     
│── frontend/          
│   ├── src/
│   │   ├── components/  
│   │   ├── pages/       
│   │   ├── App.js       
│   │   ├── index.js     
│── .env               
│── README.md         
│── package.json       



📦 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/AmriteshRaj123/stockmarket-project.git
cd real-time-stock-market

2️⃣ Backend Setup

cd backend
npm install

Create a .env file in backend/ and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string
FINNHUB_API_KEY=your_finnhub_api_key
JWT_SECRET=your_jwt_secret

Run the server:

npm run dev

3️⃣ Frontend Setup

cd frontend
npm install

Run the frontend:

npm run dev

⚡ API Endpoints (Backend)

Method

Endpoint

Description

## GET

/api/stocks/:symbol

Fetch real-time stock price

# POST

/api/watchlist/add

Add stock to user watchlist

# DELETE

/api/watchlist/remove

Remove stock from watchlist

# POST

/api/auth/register

User registration

# POST

/api/auth/login

User login

📌  Next Steps

✅ Improve UI with Material UI / Tailwind CSS✅ Add real-time search functionality✅ Implement watchlist feature with MongoDB✅ Deploy backend (Render/Railway) & frontend (Vercel)✅ Set up notifications for price alerts (optional)

