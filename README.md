# StreamVerse - Movie Streaming Platform

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/yourusername/streamverse)](https://github.com/yourusername/streamverse/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yourusername/streamverse)](https://github.com/yourusername/streamverse/network)

**StreamVerse** is a modern, responsive movie streaming platform built with HTML, CSS, and JavaScript. Featuring a Netflix-inspired UI with smooth animations, hero carousels, and dynamic content filtering.

## 🎬 Features

- **Responsive Design** - Works seamlessly on all devices (mobile, tablet, desktop)
- **Netflix-style UI** - Clean, modern interface with dark theme
- **Hero Carousel** - Auto-rotating featured content with smooth transitions
- **Dynamic Content Filtering** - Filter by categories (Movies, TV Shows, Trending)
- **Genre Navigation** - Browse by genres (Sci-Fi, Action, Fantasy, Documentaries)
- **My List Functionality** - Save your favorite titles
- **Video Player** - Integrated YouTube trailer playback
- **Search Functionality** - Find movies by title
- **Detailed View Modal** - Get more information about each title
- **Custom Toast Notifications** - User feedback for actions

## 🚀 Demo

Live Demo: [https://yourusername.github.io/streamverse](https://yourusername.github.io/streamverse)

## 📸 Screenshots

![StreamVerse Hero Section](screenshots/hero.png)
*Hero section with featured content*

![Movie Categories](screenshots/categories.png)
*Browse movies by categories*

![Details Modal](screenshots/details.png)
*Detailed view with trailer playback*

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Flexbox, Grid, Animations, Transitions
- **Tailwind CSS** - Utility-first CSS framework
- **JavaScript (ES6+)** - Modern vanilla JavaScript
- **Font Awesome** - Icons
- **YouTube API** - Video embedding

## 📁 Project Structure

```
streamverse/
├── index.html          # Main HTML file
├── README.md           # Project documentation
├── LICENSE             # MIT License
├── .gitignore          # Git ignore file
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions deployment
├── screenshots/        # Project screenshots
│   ├── hero.png
│   ├── categories.png
│   └── details.png
└── docs/               # Additional documentation
    └── SETUP.md        # Setup instructions
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JavaScript

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/streamverse.git
   cd streamverse
   ```

2. **Open in browser**
   Simply open `index.html` in your browser or use a local server:
   
   **Using Python:**
   ```bash
   python -m http.server 8000
   ```
   
   **Using Node.js:**
   ```bash
   npx serve
   ```

3. **View the application**
   Navigate to `http://localhost:8000` in your browser

## 🎯 Usage

1. **Browse Content** - Scroll through different movie categories
2. **Filter by Type** - Use navigation to filter Movies/TV Shows
3. **Filter by Genre** - Use genre tabs to narrow down content
4. **Add to My List** - Click the "+" icon on any movie card
5. **View Details** - Click the "More Info" button or card to see details
6. **Watch Trailer** - Click the play button to watch movie trailers
7. **Search** - Use the search bar to find specific titles

## 🎨 Customization

### Change Theme Colors

Modify the CSS variables in `index.html`:
```css
:root {
    --netflix-red: #E50914;
    --dark-bg: #141414;
    --card-hover-scale: 1.15;
}
```

### Add New Movies

Edit the `MOVIE_DATA` array in the JavaScript section:
```javascript
const MOVIE_DATA = [
    {
        id: 5,
        title: "New Movie",
        category: "Trending Now",
        type: "Movies",
        image: "path/to/image.jpg",
        hero: "path/to/hero-image.jpg",
        rating: "95% Match",
        year: "2024",
        cast: "Actor 1, Actor 2",
        desc: "Movie description here"
    }
];
```

### Modify Categories

Update the `CATEGORIES` array:
```javascript
const CATEGORIES = ["Trending Now", "Sci-Fi Hits", "TV Shows", "Award Winning", "New Category"];
```

## 🔧 Development

### Local Development Setup

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/AmazingFeature`
3. Make your changes
4. Commit your changes: `git commit -m 'Add some AmazingFeature'`
5. Push to the branch: `git push origin feature/AmazingFeature`
6. Open a pull request

### Code Structure

- **HTML Structure** - Semantic layout with proper sections
- **CSS Styling** - Custom properties for theming, responsive design
- **JavaScript Logic** - Modular functions for different features
- **Data Management** - In-memory data structure for movies

## 🌐 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to Repository Settings
3. Navigate to Pages section
4. Select your branch (usually `main`)
5. Your site will be available at `https://yourusername.github.io/streamverse`

### Netlify

1. Connect your GitHub repository to Netlify
2. Set build command to `# no build command`
3. Set publish directory to `/`
4. Deploy!

### Vercel

1. Import your GitHub repository in Vercel
2. Deploy with default settings
3. Your site will be live immediately

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Backend Development

For backend development and API integration, please contact:

**Chandan Pal**  
📧 Email: chandanpal2301@gmail.com

I'm available for:
- Backend API development
- Database integration
- User authentication systems
- Content management systems
- Payment gateway integration
- Real-time features

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by Netflix's user interface
- Images from Unsplash
- Icons from Font Awesome
- Built with Tailwind CSS

## 📞 Support

If you have any questions or need help:

1. Check the [Issues](https://github.com/yourusername/streamverse/issues) section
2. Create a new issue with a detailed description
3. Contact me at chandanpal2301@gmail.com for backend development inquiries

## ⭐ Show Your Support

If you like this project, please give it a star! It helps others discover it.

---

**Made with ❤️ by [Your Name]**

