# Full-Stack E-Commerce Platform

## 🌟 Project Overview

A complete **full-stack e-commerce solution** featuring:
- Next.js frontend with modern React architecture
- Node.js + TypeScript backend API
- MongoDB database integration
- Vercel deployment ready

## 🏗️ Technical Stack

### Frontend (Next.js)
- **Framework**: Next.js 14
- **Styling**: CSS Modules
- **Font Optimization**: next/font with Geist
- **State Management**: React Context
- **Deployment**: Vercel

### Backend (Node.js)
- **Runtime**: Node.js 18+
- **Language**: TypeScript
- **Package Manager**: npm
- **Development Tools**:
  - Nodemon for live reloading
  - TypeScript compiler
- **Database**: MongoDB
- **API**: RESTful endpoints

  هذا القسم يمكن أن يكون لعرض صور المشروع. إليك مثال على كيفية تنظيمه:

# 📸 Project Screenshots

## 🖥️ Frontend Views
### Home Page
![Home Page](/frontend/public/screenshots/home.png)  
*Main landing page with featured products*

### Product Listing
![Products Page](/frontend/public/screenshots/products.png)  
*Grid view of all available products*

### Shopping Cart
![Cart Page](/frontend/public/screenshots/cart.png)  
*User's shopping cart with items*

## 📱 Mobile Responsive Design
![Mobile View](/frontend/public/screenshots/mobile.png)  
*Responsive design on mobile devices*

## 🔧 Admin Dashboard
![Admin Panel](/frontend/public/screenshots/admin.png)  
*Admin interface for managing products*

## 🛠️ Backend API Examples
### API Response
```json
{
  "products": [
    {
      "id": "prod_123",
      "name": "Premium Headphones",
      "price": 199.99
    }
  ]
}
```

### Database Schema
![MongoDB Schema](/backend/screenshots/schema.png)  
*MongoDB collection relationships*

---



## 🚀 Getting Started

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```
Access at: [http://localhost:3000](http://localhost:3000)

### Backend Setup
```bash
cd backend
npm install
npm run dev
```
API runs on: [http://localhost:5000](http://localhost:5000)

## 📂 Project Structure

```
ecommerce-platform/
├── frontend/              # Next.js application
│   ├── app/               # App router directory
│   ├── public/            # Static assets
│   └── package.json       # Frontend dependencies
│
└── backend/               # Node.js API
    ├── config/            # Configuration files
    ├── src/               # TypeScript source
    ├── models/            # MongoDB schemas
    ├── routes/            # API endpoints
    └── package.json       # Backend dependencies
```

## 🔧 Development Workflow

### Frontend Development
- Edit `app/page.tsx` for main page
- Hot reloading enabled
- Component-based architecture

### Backend Development
- TypeScript compilation
- Nodemon watch mode
- MongoDB connection pooling
- Environment variables support

## 🌐 API Features

- User authentication (JWT)
- Product management (CRUD)
- Shopping cart functionality
- Order processing
- Payment gateway integration
- Admin dashboard endpoints

## 🚀 Deployment

### Frontend to Vercel
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

### Backend Options
1. **Vercel**: For serverless API routes
2. **Heroku**: Traditional Node.js hosting
3. **Railway**: Easy MongoDB integration

```bash
# Production build
npm run build
```

## 📚 Learning Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [Node.js TypeScript Guide](https://nodejs.org/en/docs/guides/typescript/)
- [MongoDB University](https://university.mongodb.com/)

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

## 📜 License

MIT License - See [LICENSE](LICENSE) for details

## 📧 Contact
- Maintainer: https://github.com/Muhamedhossafy 
- ✉️ **Email**: [muhamedammar0900@gmail.com](mailto:muhamedammar0900@gmail.com)  
- 🔗 **LinkedIn**: [Muhamad Ammar](https://www.linkedin.com/in/muhamad-ammar-18b427306)  

For support, please open an issue in the repository.
