<<<<<<< HEAD
# devChatAI
This AI-powered software uses Gemini APIs to generate code in various file formats and offers real-time chat via Socket.IO. Users can interact seamlessly with the AI for instant code generation, troubleshooting, and coding support, making it an efficient tool for developers.
=======
# MERN Stack Project with AI Integration

This project is a full-stack web application built using the MERN stack (MongoDB, Express, React, Node.js) with AI integration using Google Generative AI. The application allows users to register, log in, create projects, and collaborate with other users in real-time. The AI integration provides assistance in generating code and managing project files.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)

## Features

- User authentication (register, login, logout)
- Project creation and management
- Real-time collaboration with other users
- AI-assisted code generation and file management
- Syntax highlighting for code files
- Responsive design with Tailwind CSS

## Technologies Used

- MongoDB
- ExpressJS
- ReactJs
- TailwindCSS
- NodeJS
- socket.io
- Webcontainer
- gemini-1.5 flash
- Redis

## Installation

1. Clone the repository:

```sh
git clone https://github.com/your-username/mern-ai-project.git
cd mern-ai-project
```

2. Install dependencies for both backend and frontend:

```
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

## Usage

1. Create a .env file in both backend and frontend directories by copying the .env.sample files and filling in the required environment variables.
2. Start the backend server:

```
cd backend
npm start
```

3. Start the frontend development server:

```
cd frontend
npm start
```

4. Open your browser and navigate to http://localhost:3000 to access the application.

## Environment Variables

### Backend

Create a .env file in the backend directory with the following variables:

```
PORT=3000
JWT_SECRET=your_jwt_secret
MONGODB_URI=your_mongodb_uri
GOOGLE_AI_KEY=your_google_ai_key

# Redis
REDIS_HOST=your_redis_host
REDIS_PORT=your_redis_port
REDIS_PASSWORD=your_redis_password
```

### Frontend

Create a .env file in the frontend directory with the following variable:

```
VITE_API_URL=http://localhost:3000
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
>>>>>>> df316ce (readme.md updated)
