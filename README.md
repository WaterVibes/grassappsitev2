# GrassApp - Baltimore's Community-Focused Cannabis Delivery Platform

A 3D interactive web application showcasing Baltimore's districts with an integrated medical cannabis delivery platform.

## 🌟 Features

- Interactive 3D model of Baltimore City with district-based navigation
- Real-time 3D rendering with Three.js and Draco compression
- Responsive design for all devices
- District-specific information and services
- Comprehensive information sections:
  - About Us
  - Medical Patient Services
  - Partner Programs
  - Delivery Driver Opportunities

## 🛠️ Tech Stack

- **Frontend Framework**: Vanilla JavaScript with modern ES6+ features
- **3D Graphics**: Three.js with Draco compression
- **Build Tool**: Vite
- **Styling**: Modern CSS3 with Flexbox and Grid
- **Animation**: GSAP for smooth transitions
- **Deployment**: GitHub Pages

## 📁 Project Structure

```
grassapp/
├── public/          
│   ├── draco-decoder/  # Draco compression files
│   ├── models/         # 3D model files
│   ├── img/           # Images and assets
│   └── css/           # Compiled CSS
├── src/
│   ├── js/            # JavaScript modules
│   └── css/           # Source CSS files
├── dist/              # Production build
└── tests/             # Test files
```

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/WaterVibes/GrassAppSitev2.git
   cd GrassAppSitev2
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## 📦 Deployment

The site is deployed using GitHub Pages:

1. **Build and deploy**
   ```bash
   npm run deploy
   ```

Visit the live site at: https://watervibes.github.io/GrassAppSitev2/

## 💻 Development

- Development server runs on port 3001
- Hot Module Replacement enabled
- Source maps for debugging
- Automatic asset optimization
- CORS and security headers configured

## 🔧 Configuration

- **Vite Config**: Customized for optimal 3D model loading and compression
- **CORS**: Configured for secure cross-origin requests
- **Asset Handling**: Optimized for 3D models and textures
- **Security**: CSP headers and XSS protection enabled

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 License

MIT License - See LICENSE file for details

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

For support, email contact@grassapp.com or open an issue in the repository.

## 🙏 Acknowledgments

- Three.js community for 3D rendering support
- Draco compression team for 3D model optimization
- Baltimore City for district mapping data
