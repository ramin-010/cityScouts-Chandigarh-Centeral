# 🏙️ CityScouts Chandigarh - Central Hub

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Frontend Status](https://img.shields.io/website?down_message=offline&label=Frontend&up_message=Live&url=https%3A%2F%2Fcity-scouts-frontend.vercel.app%2F)](https://city-scouts-frontend.vercel.app/)
[![Backend Status](https://img.shields.io/website?down_message=offline&label=Backend%20API&up_message=Live&url=https%3A%2F%2Fcityscouts-backend.onrender.com)](https://cityscouts-backend.onrender.com)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ramin-010/cityScouts-Chandigarh/pulls)
[![GitHub stars](https://img.shields.io/github/stars/ramin-010/cityScouts-Chandigarh?style=social)](https://github.com/ramin-010/cityScouts-Chandigarh-Centeral)

## 🖼️ UI Screenshots

<h3>🔍 Home Page &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;       👤 Admin Dashboard &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;   🔍 Explore Page</h3>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c95ade14-7e6b-4a96-acae-b17180c86cab" alt="Home Page" width="30%" />
  &nbsp;
  <img src="https://github.com/user-attachments/assets/92812bb8-3ba7-4ee9-bcdf-7b2869dc3850" alt="Admin Dashboard" width="30%" />
  &nbsp;
  <img src="https://github.com/user-attachments/assets/ecef2a90-6a63-400c-8598-4df70708297c" alt="Explore Page" width="30%" />
</p>



## 🔗 Quick Links

### Project Repositories
- **Frontend**: [cityScouts Chandigarh – Frontend](https://github.com/ramin-010/cityScouts-frontend)  
  _React 18 • Vite • TailwindCSS • Recoil • React Query • React Router 6_

- **Backend**: [CityScouts Backend API](https://github.com/ramin-010/cityScouts-backend)  
  _Node.js • Express • MongoDB • JWT • Cloudinary • Mongoose_

### Live Demos
- **Frontend**: [city-scouts-frontend.vercel.app](https://city-scouts-frontend.vercel.app/)
- **Backend API**: [cityscouts-backend.onrender.com](https://cityscouts-backend.onrender.com)

## 🌟 Features

### Frontend Features
- 🌐 **Multi-page Application** with React Router DOM v6
- 🔍 **Advanced Search** with debounced input and instant results
- 🗺️ **Interactive Maps** using React Leaflet
- 📱 **Fully Responsive** design for all device sizes
- 👤 **User Authentication** (Login/Signup) with protected routes
- 🔒 **Role-Based Access Control** (Admin, Contributor, User)
- ❤️ **Favorites System** with persistent storage
- 📊 **Admin Dashboard** for content management
- 📝 **CRUD Operations** for attractions, dining, and events
- 🖼️ **Image Upload** with preview and management with Multer and Cloudinary
- 🎨 **Modern UI** with smooth animations using Framer Motion
- 🔄 **Infinite Scroll** with pagination support

### Backend Features
- 🔐 **JWT Authentication** with role-based access control
- 🛡️ **Security Hardening**:
  - Helmet for secure HTTP headers
  - xss-clean for XSS prevention
  - express-mongo-sanitize against NoSQL injection
  - hpp to prevent HTTP Parameter Pollution
- 📊 **Database Models**:
  - Attractions, Dining, Events, Reviews, Users
- ☁️ **Cloudinary Integration** for secure file uploads
- 🔍 **Advanced Search & Filtering** across all resources
- 📧 **Email Validation** with NeverBounce
- 📝 **Comprehensive API Documentation** with Postman
- 🚀 **High Performance** with optimized database queries

## 🛠 Tech Stack

### Frontend
- **Framework**: React 18 with Vite
- **Styling**: Tailwind CSS with custom theming
- **State Management**: Recoil
- **Routing**: React Router DOM v6
- **Maps**: React Leaflet with OpenStreetMap
- **HTTP Client**: Axios
- **Form Handling**: Custom form components with validation
- **UI Components**: Custom component library

### Backend
- **Runtime**: Node.js (v18+)
- **Framework**: Express.js (v5.1.x)
- **Database**: MongoDB (v6.x) with Mongoose (v8.16.x)
- **Authentication**: JWT with role-based access
- **File Storage**: Cloudinary with multer
- **Validation**: express-validator
- **Logging**: Morgan

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or later)
- npm (v8 or later) or yarn
- MongoDB (v6.0 or later)
- Cloudinary account (for image uploads)

### Local Development

1. **Clone the repositories**:
   ```bash
   # Frontend
   git clone https://github.com/ramin-010/cityScouts-Chandigarh-client.git
   # Backend
   git clone https://github.com/ramin-010/cityScouts-backend.git
   ```

2. **Set up the Backend**:
   ```bash
   cd cityScouts-backend/server
   npm install
   cp .env.example .env
   # Edit .env with your configuration
   npm run dev
   ```

3. **Set up the Frontend**:
   ```bash
   cd ../../cityScouts-Chandigarh-client
   npm install
   cp .env.example .env
   # Edit .env to point to your backend
   npm run dev
   ```

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact
- **Want to be an Dashboard Contributor?** : Request access raminchoudhary737@gmail.com


---

**Made with ❤️ for the City Beautiful** | [🌐 Visit Live Application](https://city-scouts-frontend.vercel.app/) | [📖 API Documentation](https://documenter.getpostman.com/view/your-doc-link)
