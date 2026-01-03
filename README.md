# 🌍 WanderLust

WanderLust is a full-stack hotel listing platform that allows users to explore, create, and manage property listings with secure authentication, image uploads, and map-based location viewing.

🔗 Live Demo: https://wanderlust-pmkf.onrender.com/listings  
Note: The site may take a few seconds to load initially as it is hosted on Render (free tier).

---

## ✨ Features

- User authentication (sign up / login / logout)
- Create, edit, and delete hotel listings (CRUD)
- Image upload and management
- Interactive map integration for property locations
- User-specific listings and access control
- Responsive UI for different screen sizes

---

## 🛠️ Tech Stack

Frontend:
- EJS
- HTML
- CSS
- JavaScript
- Bootstrap

Backend:
- Node.js
- Express.js

Database:
- MongoDB (Mongoose)

Other Tools & Services:
- Cloudinary (image storage)
- Mapbox (maps & geolocation)
- Render (deployment)

---

## 📂 Project Structure

models        – Mongoose schemas  
routes        – Express routes  
controllers   – Route logic  
views         – EJS templates  
public        – Static files (CSS, JS)  
app.js        – Main application file  

---

## 🚀 Getting Started (Local Setup)

1. Clone the repository
git clone https://github.com/your-username/wanderlust.git
cd wanderlust

2. Install dependencies
npm install

3. Create a .env file and add:
MONGO_URI=your_mongodb_connection_string  
CLOUDINARY_CLOUD_NAME=your_cloud_name  
CLOUDINARY_KEY=your_key  
CLOUDINARY_SECRET=your_secret  
MAPBOX_TOKEN=your_mapbox_token  

4. Run the project
npm start

Visit:
http://localhost:3000

---

## 🧠 What Problems This Project Solves

- Centralized platform to manage hotel listings
- Secure access control for user-generated content
- Efficient image handling using cloud storage
- Location-based discovery using maps
- Clean MVC-based backend architecture

---

## 📌 Future Improvements

- Reviews and ratings
- Wishlist / favorites
- Advanced search and filters
- Role-based access (admin panel)

---

## 👨‍💻 Author

Daniyal Ahmad

---

## 📜 License

This project is licensed under the MIT License.
