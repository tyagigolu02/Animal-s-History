# 🦁 Animal's History - Wildlife Conservation Website

A comprehensive web application dedicated to wildlife conservation and education, featuring detailed information about endangered species and ways to help protect wildlife.

![Animal Planet Logo](./assets/images/AP_logoORANGE.png)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Animals Featured](#animals-featured)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## 🌍 Overview

Animal's History is an educational wildlife conservation website that provides detailed information about various endangered species. The platform aims to raise awareness about wildlife conservation and educate visitors about the importance of protecting our planet's biodiversity.

**Mission Statement**: "The wildlife and its habitat cannot speak, so we must and we will act before it's too late."

## ✨ Features

### 🏠 Homepage
- **Hero Section**: Inspiring call-to-action for wildlife conservation
- **Conservation Actions**: Six actionable ways to save wildlife today:
  - 📚 Educate yourself
  - 🤝 Volunteer
  - 📢 Report abuse
  - 💰 Donate
  - ♻️ Recycle
  - 🌿 Preserve habitats

### 🔍 Endangered Species Gallery
- Interactive filtering system for easy navigation
- Visual cards with species information
- Responsive grid layout
- Filter by conservation status and habitat type

### 📱 Responsive Design
- Mobile-first approach
- Cross-browser compatibility
- Smooth animations and transitions
- Intuitive navigation with hamburger menu

### 🎵 Multimedia Experience
- Audio files featuring animal sounds
- Video content for select species
- High-quality image galleries
- Interactive flip cards with detailed information

### 📊 Detailed Species Profiles
Each animal page includes:
- **Basic Information**: Scientific classification, habitat, diet
- **Conservation Status**: Current population and threats
- **Physical Characteristics**: Size, weight, lifespan
- **Behavior**: Feeding habits, social structure
- **Gallery**: Multiple high-quality images
- **Population Charts**: Visual data representation

## 🦒 Animals Featured

The website showcases 12 fascinating species:

1. **🐅 Tiger** (*Panthera tigris*)
2. **🦏 Rhinos** (*Rhinocerotidae*)
3. **🦧 Orangutan** (*Pongo*)
4. **🐢 Turtle** (*Testudines*)
5. **🦅 Rhinoceros Hornbill** (*Buceros rhinoceros*)
6. **🐋 Dugong** (*Dugong dugon*)
7. **🐳 Blue Whale** (*Balaenoptera musculus*)
8. **🦅 Steppe Eagle** (*Aquila nipalensis*)
9. **🐘 Elephant** (*Elephantidae*)
10. **🐻 Bear** (*Ursidae*)
11. **🐦 Blue Jay** (*Cyanocitta cristata*)
12. **🦆 Magpie** (*Pica pica*)

## 🛠 Technologies Used

### Frontend
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with flexbox and grid
- **JavaScript (ES6+)**: Interactive functionality
- **jQuery**: DOM manipulation and event handling

### External Libraries
- **Boxicons**: Icon library for UI elements
- **Flickity**: Touch-enabled carousel slider
- **Google Fonts**: Typography (Inter font family)
- **Font Awesome**: Additional icon set

### Design Features
- CSS Grid and Flexbox for responsive layouts
- CSS Variables for consistent theming
- Smooth transitions and hover effects
- Mobile-first responsive design

## 📁 Project Structure

```
Animal-s-History/
├── 📄 index.html                 # Homepage
├── 📄 endangered-species.html    # Species gallery with filters
├── 📁 animals/                   # Individual animal pages
│   ├── 🐅 tigers.html
│   ├── 🦏 rhinos.html
│   ├── 🦧 orangutan.html
│   ├── 🐢 turtle.html
│   ├── 🦅 rhinohornbill.html
│   ├── 🐋 dugong.html
│   ├── 🐳 bluewhale.html
│   ├── 🦅 steppe-eagle.html
│   ├── 🐘 elephant.html
│   ├── 🐻 bear.html
│   ├── 🐦 blue-jay.html
│   └── 🦆 magpie.html
└── 📁 assets/
    ├── 📁 css/                   # Stylesheets
    │   ├── 🎨 main.css          # Main styles
    │   ├── 🎨 main-card.css     # Card components
    │   ├── 🎨 animal-gallery.css # Gallery layouts
    │   ├── 🎨 filter.css        # Filter functionality
    │   ├── 🎨 flip-card.css     # Flip card animations
    │   └── 🎨 table.css         # Table styling
    ├── 📁 js/                    # JavaScript files
    │   ├── ⚡ main.js           # Main functionality
    │   └── ⚡ filter.js         # Filtering logic
    ├── 📁 images/                # Image assets
    │   ├── 🖼️ Animal photos (multiple per species)
    │   ├── 📊 Population charts
    │   ├── 🎯 Icons (icon-1.png to icon-6.png)
    │   └── 🔶 AP_logoORANGE.png (Logo)
    ├── 📁 sounds/                # Audio files
    │   └── 🔊 Species-specific sounds (.mp3)
    └── 📁 videos/                # Video content
        └── 🎥 Species videos (.mp4)
```

## 🚀 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/tyagigolu02/Animal-s-History.git
   ```

2. **Navigate to project directory**:
   ```bash
   cd Animal-s-History
   ```

3. **Open in browser**:
   - Simply open `index.html` in your preferred web browser
   - Or use a local server for better performance:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     ```

4. **Access the website**:
   - Local file: `file:///path/to/Animal-s-History/index.html`
   - Local server: `http://localhost:8000`

## 🎯 Usage

### Navigation
- **Homepage**: Overview and conservation actions
- **Species Gallery**: Browse all featured animals with filtering options
- **Individual Pages**: Detailed information about each species

### Interactive Features
- **Mobile Menu**: Tap the hamburger icon for mobile navigation
- **Species Filter**: Use filter buttons on the endangered species page
- **Audio Players**: Click to hear authentic animal sounds
- **Image Galleries**: Browse through multiple photos of each species
- **Flip Cards**: Interactive cards with additional information

### Responsive Breakpoints
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🤝 Contributing

We welcome contributions to improve the Animal's History project! Here's how you can help:

### Ways to Contribute
1. **Add New Species**: Research and create pages for additional endangered animals
2. **Improve Content**: Enhance existing species information
3. **Bug Fixes**: Report and fix any issues
4. **Performance**: Optimize images, code, and loading times
5. **Accessibility**: Improve website accessibility features
6. **Translations**: Add multi-language support

### Contribution Process
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-species`)
3. Make your changes
4. Test thoroughly across different devices
5. Commit with descriptive messages (`git commit -m 'Add: Snow Leopard species page'`)
6. Push to your branch (`git push origin feature/new-species`)
7. Open a Pull Request

### Content Guidelines
- Ensure scientific accuracy of all animal information
- Use high-quality, royalty-free images
- Maintain consistent formatting across species pages
- Include reliable sources for all data

## 📧 Contact & Support

- **Repository Owner**: [tyagigolu02](https://github.com/tyagigolu02)
- **Issues**: [Report bugs or request features](https://github.com/tyagigolu02/Animal-s-History/issues)
- **Discussions**: Share ideas and get help from the community

## 🌟 Acknowledgments

- **Images**: Various wildlife photography sources
- **Icons**: Boxicons and Font Awesome icon libraries
- **Fonts**: Google Fonts (Inter family)
- **Inspiration**: Wildlife conservation organizations worldwide

## 📈 Future Enhancements

### Planned Features
- [ ] **Search Functionality**: Quick search across all species
- [ ] **Conservation News**: Latest wildlife conservation updates
- [ ] **Interactive Map**: Species distribution visualization
- [ ] **User Accounts**: Save favorite animals and track learning progress
- [ ] **Quiz Section**: Test knowledge about wildlife conservation
- [ ] **Donation Integration**: Direct links to conservation organizations
- [ ] **Social Sharing**: Share species information on social media
- [ ] **Dark Mode**: Alternative color scheme option

### Technical Improvements
- [ ] **Progressive Web App (PWA)**: Offline functionality
- [ ] **Performance Optimization**: Lazy loading for images
- [ ] **Accessibility**: WCAG 2.1 AA compliance
- [ ] **SEO Enhancement**: Better search engine optimization
- [ ] **Analytics**: Track user engagement and popular content

---

<div align="center">

**🌍 Together, we can make a difference for wildlife conservation! 🌍**

*"The greatest threat to our planet is the belief that someone else will save it."*

[![Made with ❤️ for Wildlife](https://img.shields.io/badge/Made%20with-❤️%20for%20Wildlife-green.svg)](https://github.com/tyagigolu02/Animal-s-History)

</div>
