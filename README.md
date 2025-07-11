# Admin Dashboard UI

A modern, responsive admin dashboard built with React and Vite, featuring comprehensive analytics, user management, risk monitoring, and violation tracking capabilities.

![Admin Dashboard](https://img.shields.io/badge/React-19.0.0-blue?logo=react)
![Vite](https://img.shields.io/badge/Vite-6.2.0-green?logo=vite)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.0.14-blue?logo=tailwindcss)

## 🚀 Features

### 📊 Analytics & Insights
- **AI-Powered Insights**: Advanced analytics with machine learning capabilities
- **Revenue Charts**: Comprehensive financial tracking and visualization
- **Channel Performance**: Multi-channel performance monitoring
- **Customer Segmentation**: Advanced user categorization and analysis
- **Product Performance**: Product-specific analytics and metrics
- **User Retention**: Customer retention tracking and analysis

### 👥 User Management
- **User Activity Heatmap**: Visual representation of user engagement
- **User Demographics**: Detailed demographic analysis
- **User Growth Tracking**: Growth metrics and trends
- **User Tables**: Comprehensive user data management

### ⚠️ Risk Management
- **Risk Overview**: Real-time risk assessment dashboard
- **Daily Risk Trends**: Time-series risk analysis
- **Risk by Category**: Categorized risk monitoring
- **Risk Analytics**: Advanced risk prediction and analysis

### 🚨 Violation Monitoring
- **Daily Violation Tracking**: Real-time violation monitoring
- **Violation Reports**: Comprehensive reporting system
- **Report Management**: PDF report generation and storage

### 📋 Examination System
- **Exam Management**: Complete examination workflow
- **Exam Charts**: Visual exam performance tracking
- **Exam Tables**: Detailed exam data management
- **Schedule Management**: Exam scheduling and calendar integration

### ⚙️ Settings & Configuration
- **Profile Management**: User profile customization
- **Security Settings**: Advanced security configurations
- **Notifications**: Customizable notification system
- **Connected Accounts**: Third-party account integration
- **Danger Zone**: Critical system operations

## 🛠️ Tech Stack

- **Frontend**: React 19.0.0
- **Build Tool**: Vite 6.2.0
- **Styling**: TailwindCSS 4.0.14
- **Routing**: React Router DOM 7.3.0
- **Charts**: Recharts 2.15.1
- **Animations**: Framer Motion 12.5.0
- **Icons**: Lucide React 0.479.0
- **HTTP Client**: Axios 1.8.3
- **Linting**: ESLint 9.21.0

## 📁 Project Structure

```
admin/
├── public/
│   ├── vite.svg
│   └── report/           # PDF reports storage
│       ├── p1.pdf
│       ├── p2.pdf
│       └── p3.pdf
├── src/
│   ├── Components/
│   │   ├── Sidebar.jsx
│   │   ├── analytics/    # Analytics components
│   │   ├── common/       # Shared components
│   │   ├── Exams/        # Exam-related components
│   │   ├── overview/     # Dashboard overview
│   │   ├── Risks/        # Risk management
│   │   ├── settings/     # Settings components
│   │   ├── Users/        # User management
│   │   └── violation/    # Violation tracking
│   ├── pages/            # Main page components
│   ├── App.jsx          # Main application component
│   ├── main.jsx         # Application entry point
│   └── styles/          # CSS files
├── package.json
├── vite.config.js
└── eslint.config.js
```

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd admin
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality

## 🎨 UI/UX Features

- **Responsive Design**: Fully responsive across all devices
- **Modern Gradient Backgrounds**: Beautiful gradient overlays
- **Smooth Animations**: Framer Motion powered transitions
- **Dark Theme**: Professional dark theme design
- **Interactive Charts**: Dynamic data visualization
- **Intuitive Navigation**: Easy-to-use sidebar navigation

## 📊 Dashboard Pages

1. **Overview** - Main dashboard with key metrics
2. **Analytics** - Comprehensive analytics and insights
3. **Users** - User management and analytics
4. **Exams** - Examination system management
5. **Risk** - Risk assessment and monitoring
6. **Violations** - Violation tracking and reporting
7. **Schedule** - Calendar and scheduling system
8. **Settings** - Application configuration

## 🔧 Configuration

### Environment Variables

Create a `.env` file in the root directory:

```env
VITE_API_BASE_URL=your_api_base_url
VITE_APP_TITLE=Admin Dashboard
```

### Customization

The application uses TailwindCSS for styling. You can customize the theme by modifying the Tailwind configuration or the CSS files in the `src/` directory.

## 📈 Performance

- **Fast Refresh**: Vite's Hot Module Replacement (HMR)
- **Optimized Bundle**: Tree-shaking and code splitting
- **Modern Browser Support**: ES2020+ features
- **Lazy Loading**: Route-based code splitting

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

If you encounter any issues or have questions, please create an issue in the repository or contact the development team.

## 🔮 Future Enhancements

- [ ] Real-time notifications
- [ ] Advanced filtering and search
- [ ] Export functionality for reports
- [ ] Mobile app integration
- [ ] Advanced user roles and permissions
- [ ] Multi-language support

---

**Built with ❤️ using React + Vite**
