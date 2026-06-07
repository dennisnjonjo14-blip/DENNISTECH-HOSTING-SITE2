# DENNIS TECH HOSTING SITE

## 🚀 Overview
A comprehensive hosting platform for **all programming languages** and **full-stack web applications**. Deploy your code, apps, and complete projects effortlessly with a full-screen, modern interface.

### ⭐ Key Features:
- **Multi-Language Support**: Python, JavaScript, Java, Go, Rust, PHP, C++, C#, Ruby, and more
- **Full-Stack Hosting**: Deploy complete web applications with frontend + backend
- **Project Management**: Organize multiple projects with ease
- **Real-time Monitoring**: Track performance and resource usage
- **Environment Configuration**: Set variables and manage secrets
- **Database Integration**: PostgreSQL, MongoDB, MySQL support
- **Auto-Scaling**: Scale based on traffic automatically
- **Free Tier Compatible**: Deploy on Railway/Render free tiers
- **Custom Domains**: HTTPS with custom domain binding
- **Git Integration**: Connect GitHub/GitLab repos directly
- **CI/CD Pipeline**: Automated build and deployment
- **Full-Screen UI**: Modern, responsive interface with dark theme

## 🛠️ Tech Stack

### Frontend
- React.js 18
- Tailwind CSS
- Vite
- Framer Motion (animations)
- Recharts (analytics)
- React Router DOM

### Backend
- Node.js + Express.js
- MongoDB/PostgreSQL
- JWT Authentication
- Redis (caching)
- Bcryptjs (password hashing)

### Deployment
- Docker & Docker Compose
- Railway/Render compatible
- GitHub Actions CI/CD

## 📋 Project Structure

```
DENNISTECH-HOSTING-SITE2/
├── frontend/                 # React frontend
│   ├── src/
│   │   ├── components/       # Navbar, Sidebar
│   │   ├── pages/            # Dashboard, Projects, Deploy, etc
│   │   ├── styles/           # CSS files
│   │   ├── App.jsx           # Main app
│   │   ├── main.jsx          # Entry point
│   │   └── index.css         # Global styles
│   ├── index.html            # HTML template
│   ├── vite.config.js        # Vite config
│   ├── tailwind.config.js    # Tailwind config
│   ├── Dockerfile            # Frontend Docker
│   └── package.json
├── backend/                  # Node.js backend
│   ├── routes/               # API routes
│   ├── models/               # Database models
│   ├── middleware/           # Auth middleware
│   ├── server.js             # Express server
│   ├── Dockerfile            # Backend Docker
│   └── package.json
├── docker-compose.yml        # Docker Compose setup
├── .env.example              # Environment variables
├── .gitignore                # Git ignore
├── Dockerfile                # Root Dockerfile
└── README.md                 # This file
```

## 🚀 Quick Start

### Prerequisites
- Node.js 16+
- npm/yarn
- Docker (optional)

### Installation

```bash
# Clone repository
git clone https://github.com/dennisnjonjo14-blip/DENNISTECH-HOSTING-SITE2.git
cd DENNISTECH-HOSTING-SITE2

# Install dependencies
npm install

# Setup environment
cp .env.example .env

# Start development
npm run dev
```

### Development Commands

```bash
# Run frontend only
npm run dev:frontend

# Run backend only
npm run dev:backend

# Run both (frontend + backend)
npm run dev

# Build
npm run build

# Start production
npm start
```

## 🐳 Docker Deployment

```bash
# Build and run with Docker Compose
docker-compose up --build

# Run in background
docker-compose up -d

# Stop containers
docker-compose down
```

### Ports
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000
- MongoDB: localhost:27017
- Redis: localhost:6379

## 📤 Deploy to Railway

1. Create a [Railway](https://railway.app) account
2. Connect your GitHub repository
3. Set environment variables in Railway dashboard
4. Deploy with one click

## 📤 Deploy to Render

1. Create a [Render](https://render.com) account
2. Create new Web Service
3. Connect your GitHub repository
4. Set build command: `npm run build`
5. Set start command: `npm start`
6. Deploy

## 📊 Supported Programming Languages

| Language | Status | Frameworks |
|----------|--------|-----------|
| Python | ✅ | Django, Flask, FastAPI |
| JavaScript | ✅ | Node.js, Express, Next.js |
| TypeScript | ✅ | Deno, Node.js |
| Java | ✅ | Spring Boot |
| Go | ✅ | Gin, Echo |
| Rust | ✅ | Actix, Rocket |
| PHP | ✅ | Laravel, Symfony |
| C# | ✅ | .NET Core, ASP.NET |
| Ruby | ✅ | Rails, Sinatra |
| HTML/CSS | ✅ | Static sites |

## 🔐 Security Features
- JWT-based authentication
- Password hashing with Bcryptjs
- Environment secrets management
- CORS protection
- Rate limiting support
- SSL/TLS encryption ready

## 📝 API Endpoints

### Authentication
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - Login user

### Projects
- `GET /api/projects` - Get all projects
- `POST /api/projects` - Create new project
- `GET /api/projects/:id` - Get project by ID
- `PUT /api/projects/:id` - Update project
- `DELETE /api/projects/:id` - Delete project

### Deployments
- `POST /api/deploy/start` - Start deployment
- `GET /api/deploy/:id/status` - Get deployment status
- `GET /api/deploy/:id/logs` - Get deployment logs

### Users
- `GET /api/users/me` - Get current user
- `PUT /api/users/profile` - Update profile

## 🔧 Environment Variables

See `.env.example` for complete list. Key variables:

```
PORT=5000
NODE_ENV=development
DATABASE_URL=mongodb://localhost:27017/dennistech
JWT_SECRET=your_secret_key
FRONTEND_URL=http://localhost:3000
BACKEND_URL=http://localhost:5000
```

## 📚 Features Breakdown

### 1. Project Management
- Create unlimited projects
- Support for multiple languages
- Git repository integration
- Environment variable management
- Project status tracking

### 2. Deployment
- One-click deployment
- Automated CI/CD pipeline
- Build logs and debugging
- Rollback capabilities
- Deployment history

### 3. Monitoring
- Real-time analytics
- Uptime monitoring
- Performance metrics
- Error tracking
- Resource usage

### 4. Scaling
- Auto-scaling based on traffic
- Load balancing
- Resource optimization
- Cost efficiency

## 🤝 Contributing
Contributions welcome! Please fork the repository and create a pull request.

## 📄 License
MIT License - feel free to use for personal or commercial projects

## 💬 Support
For issues and questions, open a GitHub issue or contact support.

## 👨‍💻 Author
**Dennis Njonjo** - Full Stack Developer

---

**Built with ❤️ for developers**
