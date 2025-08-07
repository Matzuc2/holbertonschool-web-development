# CSS Advanced - SmileSchool Website

A modern, responsive website for SmileSchool - an online platform for learning professional smiling techniques. This project demonstrates advanced CSS concepts including Flexbox layouts, custom styling, and responsive design principles.

## 🎯 Project Overview

SmileSchool is a fictional online learning platform that teaches various smiling techniques through video tutorials. The website features a clean, professional design with multiple sections showcasing courses, testimonials, membership options, and frequently asked questions.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all device sizes
- **Modern CSS**: Utilizes advanced CSS features including Flexbox and CSS Grid
- **Interactive Elements**: Hover effects, styled buttons, and smooth transitions
- **Video Thumbnails**: Custom play button overlays on course thumbnails
- **Star Rating System**: Visual rating display for courses
- **Professional Typography**: Source Sans Pro font family throughout
- **Background Images**: Strategic use of background images for visual appeal

## Project Structure

```
css_advanced/
├── index.html              # Main HTML structure
├── styles.css             # Complete CSS stylesheet
├── img/                   # Image assets
│   ├── header/           # Header section images
│   ├── background(1-4).png # Section backgrounds
│   └── play.png          # Video play button icon
├── videos/               # Course thumbnail images
│   ├── ratings/         # Star rating images
│   └── PhilippeMassey.png # Instructor photo
└── README.md            # This file
```

## Design Sections

### 1. Hero Section
- Eye-catching background with call-to-action
- Centered content with professional styling
- Custom button with shadow effects

### 2. Professionals Section
- Grid layout showcasing expert instructors
- Profile images with names and specializations
- Responsive card-based design

### 3. Testimonials
- Customer feedback with professional styling
- Avatar images and rating displays
- Background overlay for visual emphasis

### 4. Popular Tutorials
- Course thumbnails with play button overlays
- Star rating system (1-5 stars)
- Instructor information and course duration
- Hover effects for interactivity

### 5. Membership Section
- Pricing and benefits information
- Call-to-action button for registration
- Clean, centered layout

### 6. FAQ Section
- Expandable question and answer format
- Clean typography and spacing
- Easy-to-scan layout

### 7. Footer
- Social media icons
- Copyright information
- Professional contact details

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Advanced styling and layouts
- **Flexbox**: Primary layout system
- **Google Fonts**: Source Sans Pro typography
- **CSS Grid**: For complex layouts where needed
- **Custom Properties**: CSS variables for consistency

## Key CSS Concepts Demonstrated

### Flexbox Mastery
```css
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 30px;
}
```

### Pseudo-elements for Design
```css
.video-thumbnail::before {
    content: '';
    position: absolute;
    background-image: url('./img/play.png');
    /* Play button overlay */
}
```

### Responsive Typography
```css
h1 {
    font-family: 'Source Sans Pro', sans-serif;
    font-weight: 300;
    font-size: clamp(24px, 4vw, 60px);
}
```

### Custom Button Styling
```css
.btn-primary {
    background-color: #C271FF;
    border-radius: 30px;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
    transition: transform 0.2s ease;
}
```

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Matzuc2/holbertonschool-web-development/css_advanced.git
   cd css_advanced
   ```

2. **Open in browser**
   ```bash
   open index.html
   ```
   Or use a live server extension in your code editor.

3. **View the website**
   Navigate through different sections to see all features.

## Browser Compatibility

- ✅ Chrome (90+)
- ✅ Firefox (88+)
- ✅ Safari (14+)
- ✅ Edge (90+)

## Color Palette

- **Primary Purple**: `#C271FF`
- **Dark Text**: `#071629`
- **Light Background**: `#FFFFFF`
- **Accent Colors**: Various transparencies and gradients

## Project Requirements Met

- [x] Semantic HTML structure
- [x] Advanced CSS styling
- [x] Flexbox layouts
- [x] Custom fonts implementation
- [x] Background images and overlays
- [x] Interactive hover effects
- [x] Responsive design principles
- [x] Professional code organization

## Development Notes

### File Organization
- All styles consolidated in `styles.css`
- Images organized by section/purpose
- Clean, commented CSS for maintainability

### Performance Considerations
- Optimized image sizes
- Efficient CSS selectors
- Minimal redundant code

### Accessibility
- Semantic HTML elements
- Proper heading hierarchy
- Alt text for images
- Sufficient color contrast

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is part of the Holberton School curriculum and is for educational purposes.

## Author

**Matzuc2** - *CSS Advanced Project*
- GitHub: [@yourusername](https://github.com/Matzuc2)
- Holberton School Student

## Acknowledgments

- Holberton School for the project requirements
- Source Sans Pro font by Google Fonts
- Design inspiration from modern web trends
- Fellow students for feedback and collaboration

---

*This project demonstrates advanced CSS techniques and modern web development practices. It serves as a comprehensive example of building a professional, responsive website using