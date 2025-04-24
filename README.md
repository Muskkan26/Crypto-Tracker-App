# Crypto Tracker App

A real-time cryptocurrency price tracking web application built with *React* and *Redux Toolkit*. It simulates live price updates and displays key metrics for top crypto assets.

## Features

- Real-time price simulation (every 1–2 seconds)
- Redux Toolkit for state management
- Crypto asset details:
  - Name
  - Current Price
  - % Change (1h, 24h, 7d)
  - Market Cap
  - 24h Volume
  - Circulating Supply
  - Last 7 Days trend graph (with Recharts)
- Pagination (5 entries per page)

## Technologies Used

- React
- Redux Toolkit
- Recharts
- JavaScript (ES6+)
- CSS

## How it Works

- Uses a simulated WebSocket feed to update crypto prices every 1–2 seconds.
- State is centrally managed with Redux.
- Line graphs show the 7-day price trends per asset.

## Preview

![Screenshot 2025-04-25 022403](https://github.com/user-attachments/assets/071bbb26-6ea3-476d-9711-48bbe2eee2f2)

## Setup Instructions

```bash
git clone https://github.com/yourusername/Crypto-Tracker-App.git
cd Crypto-Tracker-App
npm install
npm start
