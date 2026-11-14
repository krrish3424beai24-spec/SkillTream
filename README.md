# SkillStream – Skill Assessment Platform

**SkillStream** is a web-based skill assessment platform designed to help users evaluate and track their skills. It provides a web interface backed by a REST API, with authentication and database integration.

## Overview

SkillStream aims to make skill evaluation more accessible through a centralized platform where users can interact with skill-related features.

The project uses a React-based frontend and a Node.js backend to provide a full-stack web application.

## Tech Stack

| Category | Technology |
|---|---|
| Frontend | React.js |
| Build Tool | Vite |
| Backend | Node.js |
| Backend Framework | Express.js |
| Database | MongoDB |
| ODM | Mongoose |
| Authentication | JWT |
| Password Security | bcryptjs |
| API Communication | Axios |
| Routing | React Router |
| Deployment | Render |

## Project Structure

```text
SkillTream/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── skillstream-mern/
│   └── backend/
│       ├── server.js
│       ├── package.json
│       └── ...
│
├── render.yaml
├── .gitignore
└── README.md
```

## Getting Started

Follow these instructions to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/krrish3424beai24-spec/SkillTream.git

cd SkillTream
```

### 2. Backend Setup

Navigate to the backend directory:

```bash
cd skillstream-mern/backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the backend directory:

```env
PORT=5000
NODE_ENV=development

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

ADMIN_EMAIL=your_admin_email
```

Start the backend:

```bash
npm run dev
```

For production:

```bash
npm start
```

### 3. Frontend Setup

Open another terminal and navigate to the frontend directory:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The Vite development server will provide a local URL in the terminal.

## Environment Variables

### Backend

| Variable | Description |
|---|---|
| PORT | Backend server port |
| NODE_ENV | Application environment |
| MONGO_URI | MongoDB connection string |
| JWT_SECRET | Secret used for JWT authentication |
| ADMIN_EMAIL | Administrator email configuration |

### Frontend

Configure the API base URL using:

```env
VITE_API_BASE_URL=http://localhost:5000/api/v1
```

The frontend should point to the backend API.

## Deployment

The repository includes a `render.yaml` configuration for deploying the application on Render.

It defines two services:

1. **Backend:** Node.js web service.
2. **Frontend:** React static site built using Vite.

Configure the required environment variables in the Render dashboard before deployment.

## Key Objectives

- Provide a centralized platform for skill assessment.
- Offer a responsive web-based user interface.
- Support secure authentication.
- Connect frontend functionality with backend APIs.
- Store application data using MongoDB.

## Future Improvements

- Add detailed skill assessment modules.
- Introduce performance analytics and progress tracking.
- Provide personalized learning recommendations.
- Add skill-based leaderboards and achievements.
- Integrate AI-powered skill evaluation.

## Author

**SkillStream Development Team**

---

**Repository:** https://github.com/krrish3424beai24-spec/SkillTream

