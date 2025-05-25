# Dialecto - Dialect Translation App

Dialecto is a modern web application that helps users translate between different dialects and languages using AI. Built with React, Node.js, and OpenAI's GPT API.

## Features

- Translate text between different dialects and languages
- Support for multiple input dialects and target languages
- Modern, responsive UI with dark mode support
- Translation history tracking
- Real-time translation using OpenAI's GPT API

## Project Structure

```
dialecto/
├── frontend/          # React frontend application
├── backend/           # Node.js backend server
└── README.md         # Project documentation
```

## Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- OpenAI API key

## Setup Instructions

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the backend directory with your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   PORT=3001
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the frontend directory:
   ```
   VITE_API_URL=http://localhost:3001
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## Deployment

### Backend Deployment
The backend can be deployed to platforms like Render, Railway, or Heroku.

### Frontend Deployment
The frontend can be deployed to Vercel, Netlify, or any static hosting service.

## Technologies Used

- Frontend:
  - React
  - Tailwind CSS
  - Axios
  - React Icons

- Backend:
  - Node.js
  - Express
  - OpenAI API
  - dotenv
  - cors

## License

MIT 