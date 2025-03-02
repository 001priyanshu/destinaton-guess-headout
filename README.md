1).# Guess Destination - Headout

This repository contains both the frontend and backend for the **Guess Destination** game.

## Project Structure
/guess-destination-headout
│── /frontend                 # Next.js Frontend
│   ├── /public               # Static assets (images, icons, etc.)
│   ├── /app
│   │   ├── /api              # Reusable UI components
│   │   ├── /pages            # Next.js pages (routes)
│   ├── /styles               # Tailwind CSS styles
│   ├── /utils                # Helper functions
│   ├── .env.local            # Environment variables
│   ├── next.config.js        # Next.js configuration
│   ├── package.json          # Dependencies and scripts
│   ├── tsconfig.json         # TypeScript config (if using TS)
│   ├── README.md             # Frontend-specific documentation
│
│── /backend                  # Node.js/Express Backend
│   ├── /src
│   │   ├── /controllers      # API request handlers
│   │   ├── /models           # Mongoose schemas
│   │   ├── /routes           # Express routes
│   │   ├── /config           # Database and server config
│   │   ├── /validators       # validator functions
│   ├── .env                  # Backend environment variables
│   ├── server.js             # Express server entry point
│   ├── package.json          # Dependencies and scripts
│   ├── README.md             # Backend-specific documentation
│
│── .gitignore                # Ignore unnecessary files
│── README.md                 # Main project documentation


## Tech Stack

### Frontend:
- **Framework**: Next.js (React)
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion

### Backend:
- **Framework**: Node.js with Express
- **Database**: MongoDB

---

## Getting Started

### 1️⃣ Clone the repository:

git clone https://github.com/001priyanshu/guess-destination-headout.git
cd guess-destination-headout

#### 2️⃣ Setup Backend
cd backend
npm install

Create a .env file in the backend directory and add:
PORT=5000
MOGOURL=your_mongodb_connection_string

Run the server:
npm start



### 3️⃣ Setup Frontend
cd ../frontend
npm install

Create a .env.local file in the frontend directory and add:
NEXT_PUBLIC_API_URL=http://localhost:5000

Run the frontend:
npm run dev


