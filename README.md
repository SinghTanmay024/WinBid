# WinBid - Online Bidding Platform

Welcome to **WinBid**, an innovative online platform where users can purchase various products through competitive bidding. Sellers can list their products and maximize their profits by selling to the highest bidder. This project is built using **Node.js** for the backend and **MongoDB** as the database.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features
- **User Registration/Login** - Secure user authentication and authorization.
- **Product Listing** - Sellers can list products with detailed descriptions and starting bid prices.
- **Bidding System** - Users can place bids on listed products within the specified time frame.
- **Real-time Updates** - Users get notified in real-time when they are outbid.
- **Auction Timer** - Countdown timer for each auction to create urgency.
- **Seller Dashboard** - Track listed products, bids, and earnings.
- **Buyer Dashboard** - Monitor active bids, winnings, and transaction history.

## Technologies Used
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Frontend:** React.js (optional, if developed)
- **Authentication:** JWT (JSON Web Tokens)
- **Real-time Communication:** Socket.IO
- **Payment Integration:** Stripe/PayPal (optional, if integrated)

## Installation

1. Clone the repository:
```bash
  git clone https://github.com/username/winbid.git
  cd winbid
```
2. Install dependencies:
```bash
  npm install
```
3. Set up environment variables:
Create a `.env` file and add the following:
```
  MONGO_URI=<your-mongodb-uri>
  JWT_SECRET=<your-jwt-secret>
  PORT=5000
```
4. Start the server:
```bash
  npm start
```

## Usage
1. Register as a user or seller.
2. Sellers can list products for bidding.
3. Users can browse products and place bids.
4. Winning bids will be notified, and transactions can proceed.

## API Endpoints
- **POST /api/auth/register** - Register a new user
- **POST /api/auth/login** - Login to your account
- **POST /api/products** - List a new product (Seller only)
- **GET /api/products** - Get all products
- **POST /api/bid/:id** - Place a bid on a product
- **GET /api/bid/user** - View user's bidding history

## Contributing
Contributions are welcome! Please fork this repository and create a pull request with detailed changes.

## License
This project is licensed under the MIT License.


![ss1](https://github.com/SinghTanmay024/WinBid/assets/106429652/c81c20c1-24b6-4154-91b7-1f85214cf468)


![ss2](https://github.com/SinghTanmay024/WinBid/assets/106429652/821c559f-3e9a-4fd2-ac76-1e176b5315f7)


![ss3](https://github.com/SinghTanmay024/WinBid/assets/106429652/c4a5a01b-df2c-418a-ace7-780b0ca5e95c)
