# 🌱 Plant Paradise - Multi-Theme Selector App

> A beautiful, responsive React application with dynamic theme switching capabilities, built with TypeScript and Tailwind CSS.

![Plant Paradise](https://img.shields.io/badge/React-19.1.1-blue?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-4.9.5-blue?logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4.17-38B2AC?logo=tailwind-css)
![License](https://img.shields.io/badge/License-ISC-green)

## ✨ Features

### 🎨 **Dynamic Theme System**
- **3 Beautiful Themes**: Switch between different visual styles instantly
- **Theme 1**: Clean & Professional (Indigo theme)
- **Theme 2**: Dark & Elegant (Teal theme) 
- **Theme 3**: Playful & Colorful (Pink/Yellow theme with custom fonts)
- **Persistent Storage**: Your theme preference is saved locally
- **Smooth Transitions**: Beautiful animations when switching themes

### 🌿 **Plant Paradise E-commerce**
- **Product Showcase**: Display products from FakeStore API
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Interactive Cards**: Beautiful product cards with images and details
- **Navigation**: Clean navigation between Home, About, and Contact pages

### 🛠 **Modern Tech Stack**
- **React 19** with TypeScript for type safety
- **Tailwind CSS** for utility-first styling
- **React Router** for seamless navigation
- **Context API** for state management
- **Axios** for API calls

## 🚀 Quick Start

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/vikrantvjoliya/multi-theme-selector-app.git
   cd multi-theme-selector-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🎯 How to Use

### Switching Themes
1. Look for the theme selector dropdown in the top-right corner of the header
2. Click on the dropdown to see available themes:
   - **Theme 1**: Professional indigo theme
   - **Theme 2**: Dark teal theme
   - **Theme 3**: Playful pink/yellow theme
3. Select your preferred theme and watch the magic happen! ✨

### Navigation
- **Home**: Browse featured products and get started
- **About**: Learn more about Plant Paradise
- **Contact**: Get in touch with us

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Button.tsx      # Custom button component
│   ├── Header.tsx      # Navigation header with theme selector
│   ├── PageContent.tsx # Page layout wrapper
│   ├── ProductCard.tsx # Product display card
│   └── ProductListItem.tsx
├── context/            # React Context for state management
│   └── ThemeContext.tsx # Theme switching logic
├── hooks/              # Custom React hooks
│   └── useTheme.ts     # Theme hook for components
├── pages/              # Page components
│   ├── HomePage.tsx    # Main landing page
│   ├── AboutPage.tsx   # About page
│   └── ContactPage.tsx # Contact page
└── App.tsx             # Main application component
```

## 🎨 Theme System Architecture

The app uses a sophisticated theme system with:

- **Theme Context**: Centralized theme state management
- **Dynamic Styling**: Tailwind classes that change based on theme
- **Custom Fonts**: Google Fonts integration (Pacifico for Theme 3)
- **Smooth Transitions**: CSS transitions for theme switching
- **Local Storage**: Theme preference persistence

### Theme Properties
Each theme includes:
- **Colors**: Primary, secondary, background, text, and UI element colors
- **Fonts**: Base and heading font families
- **Layout**: Container and content area styling
- **Spacing**: Consistent padding, margin, and gap values
- **Transitions**: Smooth animation durations

## 🛠️ Available Scripts

```bash
# Start development server
npm start

# Build for production
npm run build

# Run tests
npm test

# Eject from Create React App
npm run eject
```

## 🔧 Customization

### Adding New Themes
1. Open `src/context/ThemeContext.tsx`
2. Add a new theme object to the `themes` object
3. Include all required properties (colors, fonts, layout, spacing, transition)
4. The theme will automatically appear in the dropdown

### Modifying Existing Themes
- Edit the theme objects in `ThemeContext.tsx`
- Colors use Tailwind CSS classes
- Fonts can include Google Fonts URLs
- Layout uses Tailwind utility classes

## 🌐 API Integration

The app integrates with:
- **FakeStore API**: For product data demonstration
- **Google Fonts**: For custom typography (Theme 3)

## 📱 Responsive Design

The app is fully responsive with:
- Mobile-first design approach
- Responsive navigation (hamburger menu on mobile)
- Adaptive product grid layouts
- Touch-friendly interactive elements

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Deploy to GitHub Pages
1. Add `"homepage": "https://yourusername.github.io/repo-name"` to package.json
2. Install gh-pages: `npm install --save-dev gh-pages`
3. Add deploy script: `"deploy": "gh-pages -d build"`
4. Run: `npm run deploy`

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License.

## 🙏 Acknowledgments

- **Create React App** for the project scaffolding
- **Tailwind CSS** for the utility-first CSS framework
- **FakeStore API** for providing demo product data
- **Google Fonts** for beautiful typography

---

**Made with ❤️ and ☕ by the Plant Paradise team @vikrant**

*Ready to create your own multi-theme application? Start exploring the code and customize it to your needs!*
