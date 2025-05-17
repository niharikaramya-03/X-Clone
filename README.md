##  Features

- ⚛️ **Frontend**: React.js + TailwindCSS
- 🖥️ **Backend**: Node.js + Express.js
- 📦 **Database**: MongoDB (Mongoose)
- 🔐 **Auth**: JWT-based authentication
- ☁️ **Cloud Storage**: Cloudinary for media uploads
- 🔄 **Real-time**: Notifications via Socket.IO
- 🔍 **State Management**: React Query

### 💬 Core Functionalities

- 📝 Create & delete posts (tweets)
- 💬 Comment on posts
- ❤️ Like/unlike posts
- 🔔 Real-time notifications
- 🧑 User authentication (register/login/logout)
- 🔁 Suggested users to follow
- 🖼️ Upload profile & cover images
- ✏️ Edit profile details
- 📷 Upload post images
- 🔐 Delete only your own posts
- 🌐 Fully responsive UI
- ⏳ Loading states and skeletons

---

## 📁 Project Structure
root/
├── client/ # React frontend
│
├── server/ # Node.js backend
│ 
├── .env # Environment variables
├── README.md # Project documentation
└── .gitignore

---

## 🛠️ Setup Instructions

1️⃣ Clone the Repository

    ```bash
     git clone https://github.com/yourusername/twitter-clone-mern.git
     cd x-clone-mern

2️⃣ Setup Environment Variables
Create a .env file in the root directory and configure the following:
            
    ```bash
    MONGO_URI=your_mongodb_connection_string
    PORT=5000
    JWT_SECRET=your_jwt_secret
    NODE_ENV=development
    CLOUDINARY_CLOUD_NAME=your_cloudinary_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_secret
3️⃣ Install Dependencies
Server

    ```bash
    cd server
    npm install
Client

    ```bash
    cd client
    npm install
## Running the App
Development Mode

# In /server
    npm run dev

# In /client
    npm start
Build for Production

    cd client
    npm run build
## Deployment
You can deploy this project on platforms like:

Render / Railway / Heroku (Backend)

Vercel / Netlify (Frontend)

Make sure your production .env variables are correctly set on the hosting platform.

## Future Enhancements
DMs (Direct Messages)

Bookmark posts

Analytics (views, engagement)

Trending hashtags

Dark mode toggle

Pagination and infinite scroll
