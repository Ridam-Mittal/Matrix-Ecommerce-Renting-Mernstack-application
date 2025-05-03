# Matrix - Electronics Rental E-commerce Platform

Matrix is a full-stack web application developed using the MERN stack (MongoDB, Express.js, React.js, Node.js), built specifically to streamline the rental and purchase of electronic devices such as smartphones, laptops, and cameras. It provides a user-friendly interface for customers to browse, filter, and either rent electronics for specific durations or purchase them directly, with access to the best available rental plans.

This platform not only caters to individual users by offering a seamless shopping and rental process but also lays the foundation for future admin features such as inventory management and analytics. The use of modern technologies like JWT for authentication and Tailwind CSS for responsive design ensures that Matrix is both secure and visually appealing.

---

## Technology Stack

* **Frontend:** React.js, Tailwind CSS, React Redux
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Mongoose)
* **Authentication:** JWT, Bcrypt (for hashing passwords)

---

## Setup Instructions

1. Clone the repository and navigate to the project folder.
2. Configure environment variables in `server/.env`:

   ```
   PORT=5000
   MONGO_URI=your_mongo_connection_string
   JWT_SECRET=your_jwt_secret
   ```
3. Install dependencies and start the servers:

   ```bash
   # Server
   cd server
   npm install
   npm run dev

   # Client
   cd ../client
   npm install
   npm start
   ```

---

