# Zomato Clone Repository

![Zomato Clone](zomato-clone.png)

This repository contains a full-stack Zomato clone web application built using MERN stack (MongoDB, Express, React, and Node.js). The project aims to replicate the core functionality and user experience of the popular food delivery platform, Zomato.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Zomato Clone project is a comprehensive web application that closely mimics the layout, design, and functionality of Zomato. The application allows users to browse nearby restaurants, view their menus, place food orders, and make payments. Additionally, restaurant owners can register their establishments, manage menus, and accept incoming orders.

The project is intended to be a learning resource for developers interested in understanding how modern food delivery platforms are built. It demonstrates the implementation of various features commonly found in such applications and provides a foundation for building similar projects.

## Features

- User registration and authentication (signup, login, logout).
- Geolocation-based restaurant search.
- Restaurant details page with menu and user reviews.
- Food ordering and cart management.
- Real-time order status tracking for users and restaurants.
- Payment integration for secure transactions.
- Restaurant owner dashboard for managing orders and menus.
- Admin panel for overall application management.

## Technologies Used

-HTML  



-CSS

## Installation

To run this application locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/zomato-clone.git`
2. Navigate to the project directory: `cd zomato-clone`
3. Install frontend dependencies: `cd frontend && npm install`
4. Install backend dependencies: `cd ../backend && npm install`
5. Create a `.env` file in the `backend` directory and add the necessary environment variables (MongoDB connection string, Google Maps API key, Stripe API key, etc.).
6. Seed the database with sample data (optional): `node seeder.js` (in the `backend` directory).
7. Run the development server: `cd ../frontend && npm start` (frontend) and `cd ../backend && npm start` (backend).

## Usage

After following the installation steps, you can access the application by visiting `http://localhost:3000` in your web browser. Users can register, search for restaurants based on location, view restaurant details and menus, add food items to their cart, and complete the order by making a payment.

Restaurant owners can access the owner dashboard by logging in. They can manage incoming orders, update menus, and change order statuses. The admin panel is accessible to administrators for managing users, restaurants, and application data.

Please note that the payment functionality is integrated with Stripe's test mode, so no real transactions will occur.

## Contributing

Contributions to this project are welcome. If you find any bugs or would like to add new features or improvements, please open an issue or submit a pull request with your changes.

Before contributing, please read the [Contributing Guidelines](CONTRIBUTING.md) for detailed information on the development process, coding standards, and how to set up your development environment.




---

We hope this Zomato Clone project helps you learn more about full-stack web development and serves as a valuable resource for your learning journey. Happy coding!
