# FestFusion

FestFusion is a modern web application for managing and participating in college events. Built with React, Node.js, and MongoDB, it provides a seamless platform for event creation, registration, and management.

## Features

- 🎫 Event Creation & Management
- 👥 User Registration & Authentication
- 📱 Responsive Mobile-First Design
- 💫 Smooth Animations & Transitions
- 📝 Event Feedback System
- 👤 User Profiles
- 🎯 Event Categories & Filtering
- 📅 Event Registration System

## Tech Stack

### Frontend
- React
- Framer Motion
- Tailwind CSS
- Axios
- React Router DOM
- React Icons
- React Toastify

### Backend
- Node.js
- Express
- MongoDB
- JWT Authentication
- Bcrypt
- Multer

## Getting Started

### Prerequisites
- Node.js
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone [repository-url]
```

2. Install dependencies for both client and server
```bash
# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
```

3. Create a `.env` file in the server directory with the following variables:
```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

4. Start the development servers
```bash
# Start client (in client directory)
npm run dev

# Start server (in server directory)
npm run dev
```

## Project Structure

```
festfusion/
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/    # Reusable components
│   │   ├── pages/        # Page components
│   │   ├── AuthContext.jsx # Authentication context
│   │   └── App.jsx       # Main application component
│   └── ...
└── server/                # Backend Node.js application
    ├── models/           # MongoDB models
    ├── routes/          # API routes
    └── server.js        # Main server file
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License - see the LICENSE file for details.

## Acknowledgments

- React Icons for the icon library
- Tailwind CSS for the styling framework
- Framer Motion for animations
- MongoDB for database