# **Talkify**

Simplifying communication through chats.

## **Overview**
Talkify is a real-time chat application built with the MERN stack, enhanced by Socket.io for instant messaging and TailwindCSS + DaisyUI for a modern UI. With features like customizable themes, user presence tracking, and secure authentication, Talkify ensures seamless communication.

---

## **Features**
- 🌟 **Tech Stack**: MERN (MongoDB, Express.js, React.js, Node.js) + Socket.io + TailwindCSS + DaisyUI.
- 🎃 **Authentication & Authorization**: Secure JWT-based user authentication and role-based access control.
- 👾 **Real-Time Messaging**: Instant communication with Socket.io.
- 🚀 **Online User Status**: Track which users are online in real-time.
- 🔒 **Secure Messaging**: End-to-end encrypted chats for privacy.
- 🌙 **Dark Mode Support**: Switch between light and dark themes effortlessly.
- ⚡ **Customizable Themes**: Save and apply your favorite UI themes using DaisyUI and Zustand.
- 👌 **Global State Management**: Simplified state handling with Zustand.
- 🐞 **Error Handling**: Comprehensive error handling on both client and server.
- ⭐ **Production-Ready Deployment**: Build and deploy the app for free using the included scripts.
- ⏳ **And Much More**!

---
## **Installation**

### **Prerequisites**
- Node.js (v14+)
- MongoDB (local or hosted on MongoDB Atlas)
- Cloudinary account (for media uploads)

### **Steps**

1. Clone the repository:
   ```bash
   git clone https://github.com/123fgvvh/Talkify.git
   cd Talkify
   ```

2. Install dependencies and build the app:
   ```bash
   npm run build
   ```

3. **Setup `.env` file**:
   Create a `.env` file in the `backend` directory with the following variables:
   ```env
   MONGODB_URI=<your-mongodb-connection-string>
   PORT=5001
   JWT_SECRET=<your-secret-key>
   CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>
   CLOUDINARY_API_KEY=<your-cloudinary-api-key>
   CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>
   NODE_ENV=development
   ```

   Replace placeholders with your actual configuration values.

4. Start the application:
   ```bash
   npm start
   ```

---

## **Usage**
1. Open your browser and navigate to:
   - **Frontend**: `http://localhost:5173`
   - **Backend**: `http://localhost:5001`
2. Sign up for an account, log in, and start chatting in real-time with friends.

---

## **Scripts**

### **Build**
Builds the frontend for production and installs dependencies for both the backend and frontend:
```bash
npm run build
```

### **Start**
Starts the backend server:
```bash
npm start
```

### **Environment Setup**
Add the following to your `.env` file:
```env
MONGODB_URI=...
PORT=5001
JWT_SECRET=...
CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
NODE_ENV=development
```

---

## **Contributing**
We welcome contributions to Talkify! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request on GitHub.

## **Contact**
If you have any questions or suggestions, feel free to reach out:
- **GitHub**: [123fgvvh](https://github.com/123fgvvh)
- **Email**: <sajag.guitar@gmail.com>
