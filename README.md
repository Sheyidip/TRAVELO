# Trávelo - Travel Experience Website

## Overview
Trávelo is a modern, responsive travel website built with React and Tailwind CSS. It showcases various travel destinations and activities, providing an engaging user interface for travel enthusiasts to explore and book their next adventure.

## 🚀 Features
- Responsive design that works on desktop and mobile devices
- Interactive UI elements with hover effects and smooth transitions
- SVG illustrations for optimal performance and scalability
- Component-based architecture for easy maintenance
- Activity showcases with custom icons
- Destination cards with vector illustrations

## 📋 Prerequisites
- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)
- Basic knowledge of React and Tailwind CSS

## 🛠️ Tech Stack
- React.js
- Tailwind CSS
- shadcn/ui components
- SVG graphics
- Modern JavaScript (ES6+)

## 📥 Installation

1. Clone the repository:
```bash
git clone https://github.com/sheyidip/travelo-website.git
cd travelo-website
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit:
```
http://localhost:3000
```

## 📁 Project Structure
```
travelo-website/
├── src/
│   ├── components/
│   │   ├── TravelWebsite.jsx
│   │   └── ui/
│   │       └── card.jsx
│   ├── assets/
│   │   └── svg/
│   │       ├── hero-traveler.svg
│   │       ├── activity-icons.svg
│   │       └── destination-cards.svg
│   └── App.jsx
├── public/
├── tailwind.config.js
└── package.json
```

## 🎨 Components

### TravelWebsite
The main component that includes:
- Navigation bar
- Hero section with traveler illustration
- Activities section with interactive cards
- Destinations section with location cards

### SVG Components
- Hero Traveler: Main illustration for the hero section
- Activity Icons: Custom icons for trekking, rafting, and windsurfing
- Destination Cards: Vector illustrations for each destination

## 🎯 Usage

### Basic Implementation
```jsx
import TravelWebsite from './components/TravelWebsite';

function App() {
  return (
    <div className="app">
      <TravelWebsite />
    </div>
  );
}
```

### Customizing Destinations
```jsx
const destinations = [
  {
    location: 'Your Location',
    image: YourCustomSVG
  }
  // Add more destinations...
];
```

### Adding New Activities
```jsx
const activities = [
  {
    id: '04',
    title: 'Your Activity',
    description: 'Your Description',
    icon: YourCustomIcon
  }
  // Add more activities...
];
```

## 🔧 Configuration

### Tailwind Configuration
The project uses a custom Tailwind configuration for consistent styling:

```js
// tailwind.config.js
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {
      colors: {
        primary: '#1976d2',
        secondary: '#2196f3'
      }
    }
  },
  plugins: []
}
```

## 📱 Responsive Design
The website is fully responsive with breakpoints at:
- Mobile: 640px
- Tablet: 768px
- Desktop: 1024px

## 🤝 Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request


## 👥 Authors
- Ogundipe Abosede

## 🙏 Acknowledgments
- shadcn/ui for the component library
- Tailwind CSS team for the utility-first CSS framework
- React team for the excellent frontend library

## 📞 Support
For support, email sheyidip@gmail.com or create an issue in the repository.
