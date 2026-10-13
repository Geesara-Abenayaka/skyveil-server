# 🎵 Music Festival Management API

A robust RESTful API backend built with **Node.js** and **Express.js** to manage music festivals, concerts, and live events. It powers festival administrative controls, event lineups, stage scheduling, and ticket booking operations.

---

## 🚀 Features

- **User & Admin Authentication:** Secure signup/login using JWT and bcrypt.
- **Event & Stage Management:** Create, update, and manage festival schedules, stage allocations, and venues.
- **Artist & Lineup Details:** Manage performer profiles, performance timings, and genres.
- **Ticket Booking & Inventory:** Handle ticket tier reservations, purchase validations, and order tracking.
- **File & Media Handling:** Support for festival assets, event posters, and artist images.

---

## 🛠️ Tech Stack

- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB (via Mongoose ODM)
- **Authentication:** JSON Web Tokens (JWT) & bcrypt
- **Environment Management:** dotenv

---

## 📁 Project Structure

```text
├── Controllers/        # Request handling and business logic
├── Model/              # Database schemas and data models
├── Routes/             # API endpoints and route definitions
├── .env.example        # Environment variables template
├── .gitignore          # Ignored files and directories
├── app.js              # Application entry point and middleware configuration
├── package.json        # Dependencies and scripts
└── README.md
