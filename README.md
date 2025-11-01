# E-Learning System - Frontend

A modern, responsive E-Learning System frontend built with React and Tailwind CSS. This project provides a comprehensive learning platform with support for students, instructors, and administrators.

## 🚀 Features

### Main Pages
- **Landing Page**: Hero section, features, course categories, testimonials, and footer
- **Login/Register**: Authentication with role selection (Student, Instructor, Admin)
- **Dashboard**: Personalized dashboard with stats, recent courses, and quick actions
- **Courses Page**: Browse and search courses with filtering capabilities
- **Course Detail Page**: Detailed course view with video player, lessons, resources, and discussion
- **Admin Panel**: Complete admin interface with analytics, user management, and course management

### Key Features
- ✅ Responsive design (mobile-friendly)
- ✅ Role-based authentication and routing
- ✅ Interactive UI with Tailwind CSS
- ✅ Analytics charts using Recharts
- ✅ Search and filter functionality
- ✅ Demo data for quick testing
- ✅ AI features placeholder (Chatbot, Quiz Generator, Recommendations)

## 🛠️ Tech Stack

- **React 18** - UI library
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Styling framework
- **React Router DOM** - Routing
- **Recharts** - Analytics charts
- **Lucide React** - Icons

## 📦 Installation

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start development server:**
   ```bash
   npm run dev
   ```

3. **Build for production:**
   ```bash
   npm run build
   ```

4. **Preview production build:**
   ```bash
   npm run preview
   ```

## 📁 Project Structure

```
src/
├── components/          # Reusable components
│   └── DashboardLayout.jsx
├── context/            # React context providers
│   └── AuthContext.jsx
├── data/              # Demo data
│   └── demoData.js
├── pages/             # Page components
│   ├── LandingPage.jsx
│   ├── LoginPage.jsx
│   ├── RegisterPage.jsx
│   ├── Dashboard.jsx
│   ├── CoursesPage.jsx
│   ├── CourseDetailPage.jsx
│   └── AdminPanel.jsx
├── App.jsx            # Main app component with routing
├── main.jsx          # Entry point
└── index.css         # Global styles
```

## 🎨 Design Theme

- **Primary Color**: `#2563EB` (Blue-600)
- **Secondary Color**: `#FBBF24` (Yellow-400)
- **Background**: Light gray (`#F9FAFB`)
- **Rounded corners**: `rounded-xl`, `rounded-2xl`
- **Shadows**: `shadow-md`, `shadow-lg`, `shadow-xl`

## 🔐 Authentication

The app uses demo authentication stored in localStorage. For testing:
- Any email/password combination will work
- Select your role (Student, Instructor, Admin) during login/registration
- User session persists across page refreshes

## 📊 Demo Data

The application includes demo data for:
- Courses (6 sample courses)
- Users (3 sample users)
- Categories (6 categories)
- Testimonials (3 testimonials)
- Analytics data and charts

## 🎯 User Roles

1. **Student**: Access to courses, assignments, library, and settings
2. **Instructor**: All student features + teaching dashboard
3. **Admin**: Full access including admin panel with analytics and user/course management

## 📱 Responsive Design

- Mobile-first approach
- Hamburger menu for mobile navigation
- Responsive grids and layouts
- Touch-friendly buttons and interactions

## 🚧 Future Enhancements

- Backend API integration
- Real authentication and authorization
- Video player integration
- File upload functionality
- Real-time notifications
- Advanced search and filtering
- AI features implementation
- Dark mode support

## 📝 License

This project is created for academic/educational purposes.

## 👥 Contributing

This is a prototype frontend for an E-Learning System. Feel free to use it as a starting point for your own projects.

---

**Note**: This is a frontend-only prototype. Connect it to your backend API for full functionality.


