# Quick Chat

A real-time chat application built with React, Node.js, Express, MongoDB, and Socket.io.

## Features

- 🔐 User authentication (signup/login)
- 💬 Real-time messaging
- 👥 Friend requests system
- 🔍 User search with pagination
- 📸 Profile picture upload with Cloudinary
- 🎨 Modern UI with Tailwind CSS
- 📱 Responsive design

## Tech Stack

### Frontend
- React
- Tailwind CSS
- React Router
- Axios
- Socket.io Client
- React Hot Toast

### Backend
- Node.js
- Express
- MongoDB with Mongoose
- Socket.io
- JWT Authentication
- Cloudinary (image uploads)
- Bcrypt (password hashing)

## Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Setup

1. Clone the repository
```bash
git clone https://github.com/Ramanapenmetsa01/Quick-chat.git
cd Quick-chat
```

2. Install server dependencies
```bash
cd server
npm install
```

3. Install client dependencies
```bash
cd ../client
npm install
```

4. Create `.env` file in the server directory
```env
MONGODB_URL=your_mongodb_connection_string
PORT=5000
SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

5. Run the application

Start the server:
```bash
cd server
npm start
# or for development
nodemon server.js
```

Start the client:
```bash
cd client
npm run dev
```

## Usage

1. Sign up for a new account
2. Log in with your credentials
3. Search for users and send friend requests
4. Accept/reject friend requests
5. Start chatting with your friends!

## Project Structure

```
Quick-chat/
├── client/               # React frontend
│   ├── src/
│   │   ├── components/  # Reusable components
│   │   ├── pages/       # Page components
│   │   ├── context/     # React context
│   │   ├── lib/         # Utility functions
│   │   └── assets/      # Static assets
│   └── package.json
├── server/              # Node.js backend
│   ├── Controllers/     # Route controllers
│   ├── models/          # Mongoose models
│   ├── routes/          # API routes
│   ├── middleware/      # Custom middleware
│   ├── lib/            # Utility functions
│   └── package.json
└── README.md
```

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

MIT

## Author

Mohan Chandu
