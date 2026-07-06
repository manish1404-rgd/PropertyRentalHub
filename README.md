# 🏠 Property Rental Hub

A modern full-stack property rental platform built with **Next.js 14**, **React**, **MongoDB**, and **NextAuth**. Users can browse rental properties, search listings, authenticate securely, manage their own properties, bookmark favorites, and communicate with property owners.

---

## 🚀 Features

- 🔐 User Authentication using NextAuth
- 🏡 Browse available rental properties
- 🔍 Search properties by keywords
- ❤️ Bookmark favorite properties
- 📝 Add, Edit, and Delete property listings
- 📩 Contact property owners through messaging
- 🖼️ Upload property images using Cloudinary
- 🗺️ Interactive Maps using Mapbox
- 📱 Fully Responsive UI
- ⚡ Built with Next.js App Router

---

## 🛠️ Tech Stack

### Frontend
- Next.js 14
- React.js
- Tailwind CSS
- React Icons
- React Toastify

### Backend
- Next.js API Routes
- MongoDB
- Mongoose

### Authentication
- NextAuth.js

### Cloud Services
- Cloudinary
- Mapbox

---

## 📂 Project Structure

```
propertyRentalHub/
│
├── app/
│   ├── api/
│   ├── profile/
│   ├── properties/
│   ├── messages/
│   └── page.jsx
│
├── components/
├── context/
├── models/
├── config/
├── assets/
├── public/
├── utils/
├── middleware.js
└── package.json
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/propertyRentalHub.git
```

### Navigate to the project

```bash
cd propertyRentalHub
```

### Install dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env.local` file in the root directory and add:

```env
MONGODB_URI=your_mongodb_connection_string

NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_secret_key

GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NEXT_PUBLIC_MAPBOX_TOKEN=your_mapbox_token
```

---

## ▶️ Run the Application

```bash
npm run dev
```

Visit

```
http://localhost:3000
```

---

## 📸 Main Functionalities

- User Registration & Login
- Property Listings
- Property Details
- Property Search
- Add New Property
- Edit/Delete Property
- Bookmark Properties
- Send Messages to Property Owners
- User Dashboard
- Responsive Design

---

## 📦 Dependencies

- Next.js
- React
- MongoDB
- Mongoose
- NextAuth
- Cloudinary
- Mapbox GL
- React Map GL
- React Toastify
- Tailwind CSS

---

## 🎯 Future Improvements

- Property Reviews & Ratings
- Online Rent Payment
- Email Notifications
- Advanced Filters
- Admin Dashboard
- Real-Time Chat
- Recommendation System

---

## 👨‍💻 Author

**Manish Kumar Kuldeep**

- GitHub: https://github.com/manish1404-rgd
- 
---

## ⭐ If you found this project useful, give it a star on GitHub!
