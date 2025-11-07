# StayNest

### **A Full-Stack Vacation Rental Platform**  

 StayNest is a feature built using **Node.js, Express.js, MongoDB, HTML, CSS, and JavaScript**. This platform allows users to book vacation rentals, list properties, and manage bookings seamlessly.  

---

## **🌟 Features**  
✅ **User Authentication** – Secure login/signup with session-based authentication.  
✅ **List & Book Properties** – Users can add new properties and book available listings.  
✅ **Search & Filter** – Find rentals based on price, location, and availability.  
✅ **Responsive UI** – Fully responsive design for an optimal experience on all devices.  
✅ **Database Management** – MongoDB for storing user and listing data efficiently.  
✅ **Secure API** – Built using Express.js with proper validation and error handling.  

---

## **🛠️ Tech Stack**  
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose ORM)  
- **Authentication:** Passport.js (for user login/signup)  
- **Hosting:** Deployed on [Render/Heroku/Vercel] *(Update if applicable)*  

---

## **🚀 Installation & Setup**  

### **🔹 Prerequisites:**  
Ensure you have the following installed on your system:  
- [Node.js](https://nodejs.org/)  
- [MongoDB](https://www.mongodb.com/) *(Ensure MongoDB is running locally or use MongoDB Atlas)*  

### **🔹 Steps to Run the Project Locally**  
# Install dependencies
npm install

# Set up environment variables (Create a .env file in the root directory)
PORT=5000
MONGO_URI=your_mongodb_connection_string
SESSION_SECRET=your_secret_key

# Start the server
npm start

# Open in browser
http://localhost:5000
```


## **📂 Folder Structure**  
```bash
wanderlust/
│── public/         # Static assets (CSS, images, JS)
│── views/          # EJS/HTML templates for frontend
│── routes/         # Express.js routes (auth, listings, bookings)
│── models/         # Mongoose models (User, Listing, Booking)
│── controllers/    # Controller functions for handling requests
│── config/         # Config files (database, authentication)
│── server.js       # Main entry point for backend
│── package.json    # Dependencies & project metadata
│── .env            # Environment variables (ignored in Git)
```

---

## **📜 API Endpoints**  
| Method | Route            | Description |
|--------|-----------------|-------------|
| GET    | `/`             | Homepage |
| GET    | `/listings`     | View all properties |
| POST   | `/listings/new` | Add a new property |
| GET    | `/bookings`     | View user bookings |
| POST   | `/auth/signup`  | Register a new user |
| POST   | `/auth/login`   | Login user |
| GET    | `/auth/logout`  | Logout user |

---

## **🛡 Security Features**  
🔐 **Password Hashing** – Securely stores passwords using bcrypt.  
🔐 **Session Management** – Uses Express-session for authentication.  
🔐 **Input Validation** – Prevents SQL/NoSQL injection & XSS attacks.  

---

## **🌍 Deployment** *(Optional Section – If Deployed)*  
 
- **Backend Hosted on:** [Render]  

---

## **🛠 Future Enhancements**  
✨ **Review & Ratings System**  
✨ **Stripe Payment Integration**  
✨ **Google Maps API for Location Search**  
✨ **Multi-User Role Management (Host/Guest)**  

---

## **🤝 Contributing**  
Contributions are welcome! Feel free to fork the repository and submit pull requests.  

---

## **📬 Contact & Support**  
👨‍💻 **Amit Chaurasia**  
📧 Email: [amansk5655@gmail.com](mailto:amansk5655@gmail.com)  
🔗 LinkedIn: [www.linkedin.com/in/aman-kannaujiya-3b245323a](www.linkedin.com/in/aman-kannaujiya-3b245323a)  
🔗 GitHub: [https://github.com/kanojiyaaman](https://github.com/kanojiyaaman)  

---

### 🚀 **Star ⭐ the Repo If You Like It!**  

Would you like me to customize any sections further? 😊
