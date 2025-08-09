# House Renting App

A full-stack web application for listing, searching, and booking rental properties. Built with React (Vite) for the frontend and Node.js/Express with Prisma for the backend.

## Features

- User authentication and profile management
- List properties with images and details
- Search and filter properties by location, price, and features
- Book properties and manage bookings
- Mark properties as favourites
- Admin features for adding and managing listings

## Tech Stack

- **Frontend:** React, Vite, CSS
- **Backend:** Node.js, Express, Prisma ORM
- **Database:** JSON files (for demo), can be migrated to SQL/NoSQL
- **Deployment:** Vercel (config included)

## Getting Started

### Prerequisites
- Node.js (v18 or later recommended)
- Yarn or npm

### Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Sau1323/house_rentingapp.git
   cd house_rentingapp
   ```

2. **Install dependencies:**
   - For the backend:
     ```sh
     cd server
     yarn install
     ```
   - For the frontend:
     ```sh
     cd ../client
     yarn install
     ```

3. **Run the app locally:**
   - Start the backend:
     ```sh
     cd server
     yarn dev
     ```
   - Start the frontend:
     ```sh
     cd ../client
     yarn dev
     ```
   - The frontend will be available at `http://localhost:5173`

4. **Environment Variables:**
   - Configure `.env` files in both `server` and `client` as needed (see `.env.example` if available).

## Folder Structure

- `client/` - Frontend React app
- `server/` - Backend Express API
- `DATABASE/` - Demo data (JSON files)



