# 🏠 Real Estate Web Application (MERN Stack)

A feature-rich, scalable real estate platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This application facilitates seamless property browsing, agent-client communication via live chat, user authentication, and media management through cloud integration.

---

## 🚀 Features

- 🔐 **User Authentication**: Register/login as a property seeker or agent.
- 🏘️ **Property Management**: Add, update, delete, and browse property listings.
- 🧭 **Advanced Search Filters**: Filter by price, location, and type.
- 💬 **Live Chat Integration**: Real-time messaging between seekers and agents using `Socket.io`.
- 📊 **Agent Dashboard**: Track listings and chat history.
- ☁️ **Cloudinary Integration**: Optimized image storage and delivery.
- 🌐 **Responsive Design**: Fully responsive UI using Tailwind CSS.

---

## 🧱 Tech Stack

| Layer         | Technology           |
|---------------|----------------------|
| Frontend      | React.js, Tailwind CSS |
| Backend       | Node.js, Express.js  |
| Database      | MongoDB              |
| Real-time Chat| Socket.io            |
| Image Storage | Cloudinary           |

---

## 📂 Project Structure
real-estate-app/ ├── client/ # React Frontend │ ├── src/components/ # Reusable components │ ├── src/pages/ # Route pages │ └── src/hooks/ # Custom React hooks ├── server/ # Express Backend │ ├── controllers/ # API logic │ ├── models/ # Mongoose schemas │ ├── routes/ # API routes │ ├── middlewares/ # Auth and validation │ └── socket/ # WebSocket setup ├── .env # Environment variables ├── README.md # Project overview └── package.json # Project metadata
