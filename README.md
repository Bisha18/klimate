# 🌦️ Klimate - Modern Weather Application

A sleek and modern weather application built with TypeScript, React, and cutting-edge technologies. Klimate provides real-time weather updates, detailed forecasts, and beautiful data visualizations with a clean, responsive user interface.


## ✨ Features

### 🔍 Core Functionality
- **Real-Time Weather Data**: Get current weather conditions for any city worldwide
- **City Search**: Intuitive search functionality to find weather for any location
- **5-Day Forecast**: View detailed weather predictions for the next 5 days
- **Historical Trends**: Visualize past 10 days' temperature patterns with interactive charts
- **Geolocation Support**: Automatic location detection for instant local weather

### 🎨 User Experience
- **Dark Mode**: Eye-friendly dark theme support for better viewing experience
- **Responsive Design**: Seamless experience across desktop, tablet, and mobile devices
- **Clean UI**: Modern interface built with shadcn/ui components
- **Smooth Animations**: Polished transitions and loading states

### ⚡ Performance
- **Data Caching**: Efficient caching with TanStack Query for faster load times
- **Optimized Bundle**: Built with Vite for lightning-fast development and production builds
- **Type Safety**: Full TypeScript implementation for robust code quality

## 🛠️ Tech Stack

### Frontend Framework
- **React 18** - Modern UI library with hooks
- **TypeScript** - Type-safe JavaScript superset
- **Vite** - Next-generation frontend tooling

### State Management & Data Fetching
- **TanStack Query (React Query)** - Powerful asynchronous state management
- Automatic background refetching
- Smart caching and invalidation
- Optimistic updates

### UI Components & Styling
- **shadcn/ui** - Re-usable component library
- **Tailwind CSS** - Utility-first CSS framework
- **Recharts** - Composable charting library for data visualization
- **Lucide Icons** - Beautiful & consistent icon set

### Development Tools
- **ESLint** - Code linting and quality checks
- **PostCSS** - CSS processing and transformations

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Bisha18/klimate.git
cd klimate
```

2. **Install dependencies**
```bash
npm install
# or
yarn install
```

3. **Set up environment variables**

Create a `.env` file in the root directory:
```env
VITE_WEATHER_API_KEY=your_weather_api_key_here
VITE_WEATHER_API_URL=https://api.weatherapi.com/v1
```

> **Note**: Get your free API key from [WeatherAPI.com](https://www.weatherapi.com/)

4. **Start the development server**
```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173`

### Build for Production

```bash
npm run build
# or
yarn build
```

The optimized production build will be in the `dist` directory.

### Preview Production Build

```bash
npm run preview
# or
yarn preview
```

## 📂 Project Structure

```
klimate/
├── public/              # Static assets
├── src/
│   ├── api/            # API integration and data fetching
│   ├── components/     # React components
│   │   ├── ui/        # shadcn/ui components
│   │   └── ...        # Feature-specific components
│   ├── hooks/         # Custom React hooks
│   ├── lib/           # Utility functions and helpers
│   ├── types/         # TypeScript type definitions
│   ├── App.tsx        # Main application component
│   └── main.tsx       # Application entry point
├── .env               # Environment variables
├── package.json       # Project dependencies
├── tsconfig.json      # TypeScript configuration
└── vite.config.ts     # Vite configuration
```

## 🎯 Key Features Explained

### Smart Data Caching
Klimate uses TanStack Query to implement intelligent data caching strategies:
- Automatic background updates keep data fresh
- Stale-while-revalidate pattern for instant UI updates
- Reduced API calls for better performance and lower costs

### Interactive Temperature Charts
Historical temperature data is visualized using Recharts:
- Smooth line charts showing 10-day trends
- Interactive tooltips with detailed information
- Responsive design that works on all screen sizes

### City Search Functionality
Intuitive search with:
- Autocomplete suggestions
- Recent search history
- Geolocation-based default city
- Support for international locations

## 🌐 API Integration

Klimate integrates with WeatherAPI.com to provide:
- Current weather conditions
- 5-day detailed forecasts
- Historical weather data
- Air quality information
- Astronomy data (sunrise/sunset)

## 🎨 UI Components

Built with shadcn/ui, the app includes:
- **Search Bar**: Autocomplete city search
- **Weather Card**: Current conditions display
- **Forecast Cards**: 5-day weather preview
- **Temperature Chart**: Historical trend visualization
- **Theme Toggle**: Dark/light mode switcher
- **Loading Skeletons**: Smooth loading states

## 🔧 Configuration

### Tailwind CSS
Customized theme in `tailwind.config.js`:
- Custom color palette
- Dark mode support
- Responsive breakpoints
- Animation utilities

### TypeScript
Strict type checking enabled for:
- Enhanced code reliability
- Better IDE support
- Improved refactoring capabilities

## 📱 Responsive Design

Klimate is fully responsive with breakpoints for:
- Mobile devices (< 640px)
- Tablets (640px - 1024px)
- Desktop (> 1024px)

## 🚀 Deployment

The application is deployed on Vercel with:
- Automatic deployments from main branch
- Preview deployments for pull requests
- Edge network for global performance

Visit the live application: [klimatexyz.vercel.app](https://klimatexyz.vercel.app)

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Bishal Paul**

- GitHub: [@Bisha18](https://github.com/Bisha18)
- LinkedIn: [Bishal Paul](https://www.linkedin.com/in/bishal-paul-2897a624b/)
- Email: d.bishalpaul@gmail.com

## 🙏 Acknowledgments

- [WeatherAPI.com](https://www.weatherapi.com/) for providing the weather data API
- [shadcn/ui](https://ui.shadcn.com/) for the beautiful component library
- [TanStack Query](https://tanstack.com/query) for powerful data synchronization
- [Recharts](https://recharts.org/) for data visualization capabilities

## 📊 Project Status

This project is actively maintained and regularly updated with new features and improvements.
