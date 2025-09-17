# Store API

A simple RESTful API for handling products in a store.  
Allows creation, reading, updating, and deleting products, with data persistence via a JSON file.  

---

## Table of Contents

- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Getting Started](#getting-started)  
- [Project Structure](#project-structure)  
- [API Endpoints](#api-endpoints)  

---

## Features

- 🛒 CRUD operations on products  
- Use of controllers, routes, and middleware for modular structure  
- Data storage in JSON (via `products.json`)  
- Ability to populate initial data via a seed script  
- Basic error handling  

---

## Tech Stack

- Node.js  
- Express.js  
- JavaScript  
- File-based storage (`JSON`)  

---

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)  
- npm (comes with Node)  

### Installation

```bash
git clone https://github.com/Omar-Issa1/Store_api.git
cd Store_api
npm install
```
## API Endpoints
| Method | Path            | Description                |
| ------ | --------------- | -------------------------- |
| GET    | `/products`     | Get list of all products   |
| GET    | `/products/:id` | Get a single product by ID |
| POST   | `/products`     | Create a new product       |
| PUT    | `/products/:id` | Update a product by ID     |
| DELETE | `/products/:id` | Delete a product by ID     |
