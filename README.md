# EduTrack - Smart Learning Analytics Platform

An advanced MERN stack educational platform featuring intelligent user behavior tracking and comprehensive learning analytics with multimedia content delivery.

## 🌐 Live Deployment
- **Frontend Application**: Hosted on Vercel
- **Backend Services**: Deployed on Railway Cloud

## ✨ Key Features

- Secure user authentication and authorization
- Multi-format learning materials (articles, videos, assessments)
- Advanced user interaction analytics
- Comprehensive learning analytics dashboard
- Progress monitoring and achievement tracking
- Modern responsive UI with ShadcnUI components

## � Technology Stack

- **Frontend**: React.js with Vite bundler, ShadcnUI components
- **Backend**: Node.js with Express.js framework
- **Database**: MongoDB Atlas cloud database
- **Authentication**: JSON Web Tokens (JWT)
- **Deployment**: Vercel (frontend) & Railway (backend)

## � Application Structure

```
├── frontend/          # React client application
├── backend/           # Express.js API server
├── documentation/     # Project documentation
└── README.md         # Application overview
```

## 🔧 Setup Instructions

### Prerequisites
- Node.js (v16 or higher)
- MongoDB Atlas account
- Git

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd ET617-Assignment1
```

2. Backend Setup:
```bash
cd backend
npm install
cp .env.example .env
# Configure your environment variables
npm run dev
```

3. Frontend Setup:
```bash
cd frontend
npm install
npm run dev
```

## 🌐 Deployment

This project is deployed on Vercel: [Live Demo](#)

## 📊 Clickstream Data

The application tracks various user interactions including:
- Page views and navigation
- Video play/pause/seek actions
- Quiz attempts and submissions
- Click events and user engagement
- Session duration and patterns

## 🤝 Contributing

This is a course assignment project for ET617.

## 📝 License

This project is for educational purposes only.
