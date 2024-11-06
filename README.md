
# E-commerce Application

A full-featured e-commerce platform with admin dashboard, analytics, and caching capabilities.

## Key Features

### Product Management
- Product listing with categories
- Single product view with details
- Admin product management
- Real-time stock tracking
- Category-wise inventory management

### User Management
- User authentication
- Role-based access (Admin/Customer)
- User profile management
- Demographic tracking

### Order System
- Order processing
- Multiple order statuses (Processing, Shipped, Delivered)
- Order tracking
- Coupon system

### Analytics Dashboard
- Revenue analytics
- Sales metrics
- Inventory insights
- User demographics
- Multiple chart types:
  - Line charts (12-month trends)
  - Bar charts (6-month comparisons)
  - Pie charts (distribution analysis)

### Performance Features
- Redis caching implementation
- Cached endpoints:
  - Products
  - Categories
  - Orders
  - Analytics data
- Optimized data fetching

### Technical Stack
- Frontend: React with TypeScript
- Backend: Node.js/Express
- Database: MongoDB
- Caching: Redis
- State Management: Redux
- Charts: Moment.js for date handling

### API Endpoints
- Products: `/api/v1/product`
- Users: `/api/v1/user`
- Orders: `/api/v1/order`
- Stats: `/api/v1/stats`
- Dashboard: `/api/v1/dashboard`

## Architecture
- MVC pattern
- RESTful API design
- Middleware for error handling
- Separate controllers for different entities
- Utility functions for reusable logic

## Performance Optimizations
- Redis caching for frequently accessed data
- Efficient data aggregation
- Optimized database queries
- Proper error handling
