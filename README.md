# BoardMate

BoardMate is a full-stack collaborative online whiteboard application that enables users to create, edit, and share canvases in real-time. The project consists of a React frontend and a Node.js/Express backend with MongoDB for data storage.

## Features
- Real-time collaborative drawing
- User authentication and authorization
- Canvas sharing and access control
- Responsive and modern UI
- RESTful API backend
- Socket.IO for live updates

## Project Structure
```
BoardMate/
│
├── backend/         # Node.js/Express backend API
│   ├── config/      # Database and environment config
│   ├── controllers/ # Route controllers
│   ├── middlewares/ # Auth and other middleware
│   ├── models/      # Mongoose models
│   ├── routes/      # API routes
│   └── server.js    # Main server file
│
└── frontend/        # React frontend app
    ├── public/      # Static assets
    ├── src/         # React source code
    └── ...
```

## Getting Started

### Prerequisites
- Node.js (v16 or higher recommended)
- npm
- MongoDB Atlas or local MongoDB instance

### 1. Clone the Repository
```sh
git clone https://github.com/Ashwani-Pathak/BoardMate.git
cd BoardMate
```

### 2. Setup Backend
```sh
cd backend
npm install
# Create a .env file with your MongoDB URI and JWT secret
# Example .env:
# MONGO_URI=your_mongodb_connection_string
# JWT_SECRET=your_jwt_secret
npm start
```

### 3. Setup Frontend
```sh
cd ../frontend
npm install
# Create a .env file with your backend API URL
# Example .env:
# REACT_APP_API_URL=https://your-backend-url.onrender.com
npm start
```

## Deployment
- **Frontend:** Deploy the `frontend` folder to [Vercel](https://vercel.com/).
- **Backend:** Deploy the `backend` folder to [Render](https://render.com/).
- Set environment variables in both platforms as needed.

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](LICENSE) 