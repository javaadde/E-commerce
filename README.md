<h1 align="center"> 🛒 E-Commerce Platform </h1>

<div align="center">

![E-Commerce](https://img.shields.io/badge/E--Commerce-Platform-blue?style=for-the-badge&logo=shopping-cart)
![React](https://img.shields.io/badge/React-19.1.1-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![License](https://img.shields.io/badge/License-ISC-green?style=for-the-badge)

### 🚀 A Modern Full-Stack E-Commerce Solution

*Built with cutting-edge technologies for seamless shopping experiences*

[✨ Features](#-features) • [🛠️ Tech Stack](#️-tech-stack) • [📦 Installation](#-installation) • [🎯 Usage](#-usage) • [🤝 Contributing](#-contributing)

</div>

---

## 📖 About The Project

A comprehensive e-commerce platform featuring a responsive React frontend and robust Node.js backend. This application provides a complete online shopping experience with user authentication, product management, shopping cart functionality, and secure checkout processes.

### ✨ Features

#### 🎨 Frontend Features
- 🏠 **Modern UI/UX** - Beautiful, responsive design with TailwindCSS
- 🔐 **User Authentication** - Secure login and registration system
- 🛍️ **Product Catalog** - Browse products with advanced filtering
- 🛒 **Shopping Cart** - Add, remove, and manage cart items
- 💳 **Checkout Process** - Streamlined payment flow
- 📱 **Responsive Design** - Works seamlessly on all devices
- 🔍 **Search Functionality** - Find products quickly
- ⭐ **Product Reviews** - Rate and review products

#### ⚙️ Backend Features
- 🔒 **Secure Authentication** - BCrypt password hashing
- 💾 **MongoDB Integration** - Efficient data management
- 📸 **Image Upload** - Cloudinary integration for product images
- 🛡️ **Input Validation** - Express-validator for data integrity
- 🔄 **Session Management** - Secure user sessions with MongoDB store
- 🌐 **RESTful API** - Well-structured API endpoints
- 🚀 **CORS Enabled** - Cross-origin resource sharing support

---

## 🛠️ Tech Stack

### Frontend 🎨

| Technology | Purpose |
|------------|---------|
| ![React](https://img.shields.io/badge/React-19.1.1-61DAFB?logo=react&logoColor=black) | UI Framework |
| ![Vite](https://img.shields.io/badge/Vite-7.1.6-646CFF?logo=vite&logoColor=white) | Build Tool |
| ![TailwindCSS](https://img.shields.io/badge/Tailwind-4.1.13-38B2AC?logo=tailwind-css&logoColor=white) | Styling |
| ![React Router](https://img.shields.io/badge/React_Router-7.9.1-CA4245?logo=react-router&logoColor=white) | Routing |
| ![Axios](https://img.shields.io/badge/Axios-1.12.2-5A29E4?logo=axios&logoColor=white) | HTTP Client |
| ![React Hook Form](https://img.shields.io/badge/React_Hook_Form-7.63.0-EC5990?logo=reacthookform&logoColor=white) | Form Management |
| ![Lucide React](https://img.shields.io/badge/Lucide-Icons-F56565) | Icons |
| ![Yup](https://img.shields.io/badge/Yup-Validation-orange) | Schema Validation |

### Backend ⚙️

| Technology | Purpose |
|------------|---------|
| ![Node.js](https://img.shields.io/badge/Node.js-Runtime-339933?logo=node.js&logoColor=white) | Server Runtime |
| ![Express](https://img.shields.io/badge/Express-5.1.0-000000?logo=express&logoColor=white) | Web Framework |
| ![MongoDB](https://img.shields.io/badge/MongoDB-8.18.1-47A248?logo=mongodb&logoColor=white) | Database |
| ![Cloudinary](https://img.shields.io/badge/Cloudinary-2.7.0-3448C5?logo=cloudinary&logoColor=white) | Image Storage |
| ![BCrypt](https://img.shields.io/badge/BCrypt-6.0.0-red) | Password Hashing |
| ![Multer](https://img.shields.io/badge/Multer-2.0.2-orange) | File Upload |
| ![Express Validator](https://img.shields.io/badge/Express_Validator-7.2.1-blue) | Input Validation |

---

## 📦 Installation

### Prerequisites 📋

Before you begin, ensure you have the following installed:
- 🟢 **Node.js** (v16 or higher)
- 📦 **npm** or **yarn**
- 🍃 **MongoDB** (local or Atlas)
- ☁️ **Cloudinary Account** (for image uploads)

### Clone the Repository 📥

```bash
git clone https://github.com/javaadde/E-commerce.git
cd E-commerce
```

### Backend Setup 🔧

1️⃣ Navigate to the backend directory:
```bash
cd backend
```

2️⃣ Install dependencies:
```bash
npm install
```

3️⃣ Create a `.env` file in the backend root:
```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_session_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

4️⃣ Start the backend server:
```bash
npm start
```

The backend will run on `http://localhost:5000` 🚀

### Frontend Setup 🎨

1️⃣ Open a new terminal and navigate to the frontend directory:
```bash
cd frontend
```

2️⃣ Install dependencies:
```bash
npm install
```

3️⃣ Create a `.env` file in the frontend root:
```env
VITE_API_URL=http://localhost:5000/api
```

4️⃣ Start the development server:
```bash
npm run dev
```

The frontend will run on `http://localhost:5173` 🎉

---

## 🎯 Usage

### Running the Application 🏃‍♂️

1. **Start MongoDB** 🍃
   ```bash
   mongod
   ```

2. **Start Backend Server** ⚙️
   ```bash
   cd backend
   npm start
   ```

3. **Start Frontend Development Server** 🎨
   ```bash
   cd frontend
   npm run dev
   ```

4. **Access the Application** 🌐
   - Frontend: `http://localhost:5173`
   - Backend API: `http://localhost:5000/api`

### Building for Production 🏗️

#### Frontend Build
```bash
cd frontend
npm run build
npm run preview
```

---

## 📁 Project Structure

```
E-commerce/
├── 📂 backend/
│   ├── 📂 config/          # Configuration files
│   ├── 📂 controllers/     # Route controllers
│   ├── 📂 models/          # Database models
│   ├── 📂 routes/          # API routes
│   ├── 📂 middleware/      # Custom middleware
│   ├── 📂 utils/           # Utility functions
│   ├── 📄 app.js           # Express app setup
│   └── 📄 package.json     # Backend dependencies
│
├── 📂 frontend/
│   ├── 📂 src/
│   │   ├── 📂 components/  # React components
│   │   ├── 📂 pages/       # Page components
│   │   ├── 📂 hooks/       # Custom hooks
│   │   ├── 📂 utils/       # Utility functions
│   │   ├── 📂 services/    # API services
│   │   ├── 📄 App.jsx      # Main App component
│   │   └── 📄 main.jsx     # Entry point
│   ├── 📄 index.html       # HTML template
│   ├── 📄 vite.config.js   # Vite configuration
│   └── 📄 package.json     # Frontend dependencies
│
└── 📄 README.md            # You are here! 📍
```

---

## 🔑 API Endpoints

### Authentication 🔐
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - User login
- `POST /api/auth/logout` - User logout
- `GET /api/auth/profile` - Get user profile

### Products 🛍️
- `GET /api/products` - Get all products
- `GET /api/products/:id` - Get single product
- `POST /api/products` - Create product (Admin)
- `PUT /api/products/:id` - Update product (Admin)
- `DELETE /api/products/:id` - Delete product (Admin)

### Cart 🛒
- `GET /api/cart` - Get user cart
- `POST /api/cart` - Add item to cart
- `PUT /api/cart/:id` - Update cart item
- `DELETE /api/cart/:id` - Remove from cart

### Orders 📦
- `POST /api/orders` - Create order
- `GET /api/orders` - Get user orders
- `GET /api/orders/:id` - Get order details

---

## 🎨 Screenshots

> 📸 Add screenshots of your application here to showcase its features!

---

## 🤝 Contributing

Contributions are what make the open-source community amazing! Any contributions you make are **greatly appreciated**. ❤️

1. 🍴 Fork the Project
2. 🌿 Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to the Branch (`git push origin feature/AmazingFeature`)
5. 🔀 Open a Pull Request

---

## 📝 License

Distributed under the ISC License. See `LICENSE` for more information.

---

## 👨‍💻 Author

**Your Name**

- 🐙 GitHub: [@javaadde](https://github.com/javaadde)
- 📧 Email: your.email@example.com
- 💼 LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)

---

## 🙏 Acknowledgments

- 💡 [React Documentation](https://react.dev/)
- 🎨 [TailwindCSS](https://tailwindcss.com/)
- 🚀 [Vite](https://vitejs.dev/)
- 🍃 [MongoDB](https://www.mongodb.com/)
- ⚡ [Express.js](https://expressjs.com/)
- ☁️ [Cloudinary](https://cloudinary.com/)
- 🎯 [Lucide Icons](https://lucide.dev/)

---

<div align="center">

### ⭐ Don't forget to give this project a star if you found it helpful! ⭐

Made with ❤️ and ☕

</div>