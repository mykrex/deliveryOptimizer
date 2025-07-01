# Delivery Optimizer 🚚

A smart route optimization system for delivery services using advanced algorithms to minimize travel time and maximize efficiency.

## 🏗️ Architecture

- **Frontend**: Next.js + React + TypeScript + Tailwind CSS
- **API Gateway**: Node.js + Express + TypeScript
- **Optimizer Engine**: Python + FastAPI + Google OR-Tools
- **Database**: PostgreSQL + Redis

## 🚀 Quick Start

```bash
# Install all dependencies
npm run install:all

# Start all services
npm run dev:all
```

## 📋 Services

| Service | Port | Description |
|---------|------|-------------|
| Frontend | 3000 | React dashboard with maps |
| Backend API | 5000 | REST API and authentication |
| Python Optimizer | 8000 | Route calculation engine |

## 🎯 Features

- **Real-time route optimization** using Vehicle Routing Problem (VRP) algorithms
- **Interactive maps** with Google Maps integration
- **Performance analytics** and delivery metrics
- **Multi-vehicle support** with capacity constraints
- **Time windows** and priority delivery handling

## 🛠️ Development

```bash
# Run individual services
npm run dev:frontend   # Start React app
npm run dev:backend    # Start Node.js API
npm run dev:python     # Start Python optimizer

# Build for production
npm run build:frontend
```

## 📊 Tech Stack Details

- **OR-Tools**: Google's optimization library for VRP solving
- **PostgreSQL**: Delivery data, routes, and user management
- **Redis**: Caching optimized routes and session data
- **Google Maps API**: Geocoding and distance calculations

---

Built with ❤️ & 🤖, for efficient deliveries