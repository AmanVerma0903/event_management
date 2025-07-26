# 🎉 CelebrateIt - Event Management System

A modern, full-stack event management application built with React.js and Node.js, designed to help users plan and organize various types of events with ease.

## ✨ Features

- **Responsive Design**: Modern, mobile-friendly UI with smooth animations
- **Event Categories**: Support for multiple event types including:
  - 🎂 Birthday Parties
  - 💒 Weddings
  - 🏕️ Camping Trips
  - 🎮 Game Nights
  - 🍽️ Restaurant Events
  - 🎊 General Parties
  - 🎉 Anniversary Celebrations
- **Contact Form**: Integrated messaging system with backend support
- **Smooth Scrolling**: Seamless navigation between sections
- **Modern UI/UX**: Beautiful design with React Icons and animations
- **Backend API**: RESTful API with MongoDB database
- **Real-time Notifications**: Toast notifications for user feedback

## 🛠️ Tech Stack

### Frontend
- **React.js** - Modern UI library
- **Vite** - Fast build tool and development server
- **React Router DOM** - Client-side routing
- **React Scroll** - Smooth scrolling navigation
- **React Icons** - Beautiful icon library
- **React Hot Toast** - Toast notifications
- **Axios** - HTTP client for API calls
- **CSS3** - Styling and animations

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **CORS** - Cross-origin resource sharing
- **Dotenv** - Environment variable management
- **Validator** - Data validation

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local installation or MongoDB Atlas)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/event-management.git
   cd event-management
   ```

2. **Install Frontend Dependencies**
   ```bash
   cd frontend
   npm install
   ```

3. **Install Backend Dependencies**
   ```bash
   cd ../backend
   npm install
   ```

4. **Environment Setup**
   
   Create a `.env` file in the `backend/config/` directory:
   ```env
   PORT=4000
   MONGODB_URI=your_mongodb_connection_string
   NODE_ENV=development
   ```

5. **Start the Development Servers**

   **Backend (Terminal 1):**
   ```bash
   cd backend
   npm run dev
   ```
   The backend server will start on `http://localhost:4000`

   **Frontend (Terminal 2):**
   ```bash
   cd frontend
   npm run dev
   ```
   The frontend application will start on `http://localhost:5173`

## 📁 Project Structure

```
event_management/
├── frontend/                 # React.js frontend application
│   ├── public/              # Static assets
│   ├── src/
│   │   ├── components/      # React components
│   │   │   ├── About.jsx
│   │   │   ├── Contact.jsx
│   │   │   ├── Footer.jsx
│   │   │   ├── HeroSection.jsx
│   │   │   ├── Navbar.jsx
│   │   │   └── Services.jsx
│   │   ├── App.jsx          # Main application component
│   │   └── main.jsx         # Application entry point
│   └── package.json
├── backend/                  # Node.js backend application
│   ├── config/              # Configuration files
│   ├── controller/          # Route controllers
│   ├── database/            # Database connection
│   ├── models/              # MongoDB schemas
│   ├── router/              # API routes
│   ├── app.js               # Express app configuration
│   └── server.js            # Server entry point
└── README.md
```

## 🎯 API Endpoints

### Message API
- `POST /api/v1/message` - Send a new message/contact form

## 🎨 Features in Detail

### Home Section
- Hero section with compelling call-to-action
- Smooth scrolling navigation
- Responsive design for all devices

### Services Section
- Showcase of different event types
- Beautiful event category cards
- Interactive hover effects

### About Section
- Company information and mission
- Professional presentation

### Contact Section
- Contact form with validation
- Real-time form submission
- Success/error notifications

## 🔧 Available Scripts

### Frontend
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

### Backend
- `npm start` - Start production server
- `npm run dev` - Start development server with nodemon

## 🌐 Deployment

### Frontend Deployment
1. Build the application:
   ```bash
   cd frontend
   npm run build
   ```
2. Deploy the `dist` folder to your preferred hosting service (Vercel, Netlify, etc.)

### Backend Deployment
1. Set up environment variables on your hosting platform
2. Deploy to platforms like Heroku, Railway, or DigitalOcean
3. Ensure MongoDB connection string is properly configured



## 👨‍💻 Author

**Aman Verma**



## 🙏 Acknowledgments

- React.js community for the amazing framework
- MongoDB for the robust database solution
- All the open-source libraries that made this project possible



---

