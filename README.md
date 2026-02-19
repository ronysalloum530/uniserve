# UniServe AI Platform

🚀 **Complete Full-Stack AI Services Platform**

## 📋 Project Overview

UniServe AI is a comprehensive platform offering AI-powered services including:
- 🎓 **Educational Services** - Courses and training programs
- 💼 **Professional Consultation** - AI consulting services
- 🔒 **Cybersecurity Solutions** - Security assessment and protection
- 🛒 **Marketplace** - AI products and bundles
- 🎯 **Custom Development** - Tailored AI solutions

## 🏗️ Architecture

### Backend (Node.js + Express)
- **Framework**: Express.js with TypeScript support
- **Database**: MongoDB with Mongoose ODM
- **Authentication**: JWT with bcrypt password hashing
- **Security**: Helmet, CORS, Rate Limiting, XSS Protection
- **File Upload**: Multer with image processing
- **Email Service**: Nodemailer integration
- **Payment**: Stripe integration
- **Real-time**: Socket.io for live features
- **API Documentation**: Swagger/OpenAPI

### Frontend (HTML/CSS/JavaScript)
- **Framework**: Vanilla JavaScript with ES6+ features
- **Styling**: Modern CSS with responsive design
- **UI Components**: Custom component system
- **State Management**: LocalStorage + API integration
- **Authentication**: JWT token-based auth
- **Real-time**: Socket.io client integration

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- MongoDB 5.0+
- Git

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/uniserve-ai.git
cd uniserve-ai
```

2. **Install Backend Dependencies**
```bash
cd backend
npm install
```

3. **Setup Environment Variables**
```bash
cp .env.example .env
# Edit .env with your configuration
```

4. **Start MongoDB**
```bash
mongod
```

5. **Start Backend**
```bash
npm run dev
```

6. **Start Frontend**
```bash
cd ../UNSER1
npx serve . -p 3000
```

### Quick Start Scripts
- **Windows**: `start-quick.bat` (Double-click)
- **PowerShell**: `.\start-quick.ps1`
- **Manual**: Follow steps above

## 🌐 Access Points

- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:5001
- **API Documentation**: http://localhost:5001/api-docs

## 📱 Features

### 🔐 Authentication
- User registration and login
- JWT token-based authentication
- Password hashing with bcrypt
- Session management

### 🛒 Marketplace
- Product catalog with categories
- Shopping cart functionality
- Order management
- Payment integration with Stripe

### 🎓 Education
- Course listings and enrollment
- Progress tracking
- Interactive learning modules
- Certificate generation

### 💼 Consultation
- AI consultation booking
- Real-time chat support
- Expert matching
- Session management

### 🔒 Cybersecurity
- Security assessment tools
- Vulnerability scanning
- Protection recommendations
- Security reports

### 📊 Admin Panel
- User management
- Order tracking
- Analytics dashboard
- Content management

## 🔧 Configuration

### Environment Variables
```env
# Database
MONGODB_URI=mongodb://localhost:27017/unser1

# JWT
JWT_SECRET=your-secret-key

# Email
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-app-password

# Stripe
STRIPE_SECRET_KEY=sk_test_your-key
STRIPE_PUBLISHABLE_KEY=pk_test_your-key

# Server
PORT=5001
FRONTEND_URL=http://localhost:3000
```

## 📚 API Documentation

### Authentication Endpoints
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `GET /api/auth/me` - Get current user

### Product Endpoints
- `GET /api/products` - Get all products
- `GET /api/products/:id` - Get product by ID
- `POST /api/products` - Create product (admin)

### Order Endpoints
- `GET /api/orders` - Get user orders
- `POST /api/orders` - Create order
- `PUT /api/orders/:id` - Update order

## 🧪 Testing

### Backend Tests
```bash
cd backend
npm test
```

### Frontend Testing
Open browser developer tools and check console for any errors.

## 🐳 Docker Support

```bash
docker-compose up -d
```

## 📦 Deployment

### Backend Deployment
1. Set production environment variables
2. Build: `npm run build`
3. Start: `npm start`

### Frontend Deployment
1. Build static files
2. Deploy to any static hosting service
3. Configure API endpoints

## 🤝 Contributing

1. Fork the repository
2. Create feature branch
3. Make your changes
4. Submit pull request

## 📄 License

This project is licensed under the MIT License.

## 📞 Support

For support and inquiries:
- Email: support@uniserve-ai.com
- GitHub Issues: [Create Issue](https://github.com/yourusername/uniserve-ai/issues)

## 🙏 Acknowledgments

- Node.js and Express.js community
- MongoDB and Mongoose
- Stripe for payment processing
- All open source contributors

---

**Built with ❤️ by UniServe AI Team**
