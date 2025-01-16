# Price Tracker Website

A web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack that tracks the prices of products from Amazon and Flipkart, notifies users of price drops via email alerts, and allows product management through a user-friendly dashboard.

---

## Features

- **User Authentication:**
  - Login and registration using Google OAuth.
- **Product Price Tracking:**
  - Add product links from Amazon and Flipkart.
  - Automatically fetch and store product details and prices.
  - Periodic price checking and tracking.
- **Email Alerts:**
  - Notify users when product prices drop below the desired threshold.
- **Dashboard:**
  - Manage tracked products in a user-friendly interface.
- **Database Management:**
  - Store product and user data securely using MongoDB.

---

## Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (NoSQL)
- **Authentication:** Google OAuth 2.0
- **Scraping Library:** Axios/Cheerio or Puppeteer
- **Email Notifications:** NodeMailer

---

## Installation

**Clone the Repository**
   ```bash
   git clone https://github.com/natalrhyme/price-tracker.git
   cd price-tracker
   ```
**Create a `.env` file and add the following variables**
  ```bash
  MONGO_URI=your_mongo_db_connection_string
  PORT=5000
  GOOGLE_CLIENT_ID=your_google_client_id
  GOOGLE_CLIENT_SECRET=your_google_client_secret
  NODEMAILER_EMAIL=your_email
  NODEMAILER_PASSWORD=your_email_password
  ```
**Run the Application**
   - Open your browser and navigate to `http://localhost:3000`.

---

## Usage

1. Register or log in using your Google account.
2. Add product links from Amazon or Flipkart on the dashboard.
3. The application will track the product prices periodically.
4. Receive email alerts when prices drop.

---

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

---

