# spotify-clone
 # Spotify Clone - Full Stack MERN Application

A full-stack Spotify clone built with the MERN stack (MongoDB, Express, React, Node.js) that replicates core Spotify functionality including music streaming, playlist management, and user authentication.

## 🚀 Features

- **User Authentication**: Sign up, login, and user session management
- **Music Library**: Browse and search through music collections
- **Playlist Management**: Create, edit, and delete custom playlists
- **Music Player**: Full-featured music player with playback controls
- **Responsive Design**: Mobile-friendly interface using Tailwind CSS
- **File Upload**: Support for audio file uploads with Cloudinary integration
- **Admin Panel**: Administrative interface for content management

## 🛠️ Tech Stack

### Frontend (spotify-clone-f)
- **React 18** - Modern React with hooks
- **Vite** - Fast build tool and development server
- **React Router DOM** - Client-side routing
- **Axios** - HTTP client for API requests
- **Tailwind CSS** - Utility-first CSS framework
- **PostCSS** - CSS transformation tool

### Backend (spotify-backend)
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework for Node.js
- **MongoDB** - NoSQL database with Mongoose ODM
- **Cloudinary** - Cloud media management
- **Multer** - Middleware for handling file uploads
- **CORS** - Cross-Origin Resource Sharing
- **dotenv** - Environment variable management

## 📁 Project Structure

```
spotify-full-stack/
├── spotify-clone-f/          # Frontend React application
│   ├── public/               # Static assets
│   ├── src/                  # React source code
│   ├── package.json          # Frontend dependencies
│   └── vite.config.js        # Vite configuration
├── spotify-backend/          # Backend Node.js application
│   ├── src/                  # Backend source code
│   ├── server.js             # Main server file
│   ├── package.json          # Backend dependencies
│   └── .env                  # Environment variables
└── README.md                 # This file
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- MongoDB (local or Atlas)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd spotify-full-stack
   ```

2. **Install Backend Dependencies**
   ```bash
   cd spotify-backend
   npm install
   ```

3. **Install Frontend Dependencies**
   ```bash
   cd ../spotify-clone-f
   npm install
   ```

### Environment Setup

1. **Create environment file in backend**
   ```bash
   cd spotify-backend
   touch .env
   ```

2. **Add the following environment variables**
   ```env
   MONGODB_URI=your_mongodb_connection_string
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   JWT_SECRET=your_jwt_secret_key
   PORT=5000
   ```

### Running the Application

1. **Start the Backend Server**
   ```bash
   cd spotify-backend
   npm run server
   ```
   The backend will run on `http://localhost:5000`

2. **Start the Frontend Development Server**
   ```bash
   cd spotify-clone-f
   npm run dev
   ```
   The frontend will run on `http://localhost:5173` (or another available port)

## 📚 Available Scripts

### Backend (spotify-backend)
- `npm run server` - Start the development server with nodemon

### Frontend (spotify-clone-f)
- `npm run dev` - Start the development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🔧 API Endpoints

The backend API provides the following endpoints:

- **Authentication**: `/api/auth/*`
- **Users**: `/api/users/*`
- **Songs**: `/api/songs/*`
- **Playlists**: `/api/playlists/*`
- **Upload**: `/api/upload/*`

## 🎯 Key Features Implementation

### Music Streaming
- Audio file upload and storage using Cloudinary
- Stream music with playback controls
- Progress tracking and time display

### User Management
- Secure user registration and login
- JWT-based authentication
- User profile management

### Playlist System
- Create custom playlists
- Add/remove songs from playlists
- Playlist sharing and visibility settings

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the ISC License - see the package.json file for details.

## 🙏 Acknowledgments

- Spotify for the design inspiration
- Cloudinary for media storage services
- The MERN stack community for excellent tools and libraries

## 📞 Support

For any questions or support, please open an issue in the repository or contact the development team.

---

**Note**: This is a clone project for educational purposes. All music and content used should be properly licensed or owned by the user.

