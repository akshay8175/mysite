# Software Engineer Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Perfect for software engineers and developers to showcase their skills, projects, and experience.

## 🚀 Features

- **Fully Responsive Design** - Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Interactive Elements** - Typing animation, skill progress bars, smooth scrolling
- **Mobile-First Approach** - Optimized for mobile devices with hamburger menu
- **Performance Optimized** - Lazy loading, debounced events, optimized animations
- **Accessibility Features** - Keyboard navigation, focus management, ARIA attributes
- **Contact Form** - Built-in form validation with notification system
- **Customizable** - Easy to customize colors, content, and sections

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── main.js         # JavaScript functionality
├── images/             # Image assets
│   ├── profile-photo.jpg
│   ├── about-photo.jpg
│   ├── project1.jpg
│   ├── project2.jpg
│   └── project3.jpg
├── assets/             # Other assets
│   └── resume.pdf      # Downloadable resume
└── README.md           # This file
```

## 🎨 Customization Guide

### 1. Personal Information
Edit the following sections in `index.html`:

- **Name and Title**: Update the `<h1>` and `<h3>` tags in the home section
- **Description**: Modify the paragraph in the home section
- **Contact Information**: Update phone, email, and location in the contact section
- **Social Media Links**: Update LinkedIn, GitHub, and Twitter URLs

### 2. About Section
- Replace the about description with your own
- Update the statistics (projects completed, years of experience, companies worked)
- Replace the profile photo (`images/profile-photo.jpg`)

### 3. Skills Section
- Modify skill categories (Frontend, Backend, DevOps)
- Update skill names and percentages
- Add or remove skills as needed

### 4. Projects Section
- Replace project images (`images/project1.jpg`, etc.)
- Update project titles, descriptions, and technologies
- Add your actual demo and GitHub links

### 5. Experience Section
- Update education information
- Modify work experience details
- Add or remove entries as needed

### 6. Colors and Styling
In `css/style.css`, you can customize:

- **Primary Color**: Change the `--hue-color` variable (line 10)
  - Blue: 230 (default)
  - Green: 142
  - Purple: 250
  - Pink: 340
  - Or any value between 0-360

- **Fonts**: Modify the `--body-font` variable to use different Google Fonts

### 7. Adding Your Images

Replace these placeholder images with your own:

- `images/profile-photo.jpg` - Your profile photo (recommended: 400x400px)
- `images/about-photo.jpg` - About section photo (recommended: 350x400px)
- `images/project1.jpg` - Project 1 screenshot (recommended: 400x300px)
- `images/project2.jpg` - Project 2 screenshot (recommended: 400x300px)
- `images/project3.jpg` - Project 3 screenshot (recommended: 400x300px)

### 8. Resume/CV
- Replace `assets/resume.pdf` with your actual resume

## 🛠️ Setup Instructions

1. **Clone or Download** the portfolio files
2. **Customize** the content as described above
3. **Add Your Images** to the `images/` folder
4. **Update Your Resume** in the `assets/` folder
5. **Test** the website locally by opening `index.html` in a browser

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Deployment

You can deploy this portfolio to any web hosting service:

### Free Options:
- **GitHub Pages** - Push to a GitHub repository and enable Pages
- **Netlify** - Drag and drop the folder to Netlify
- **Vercel** - Connect your GitHub repository
- **Firebase Hosting** - Use Firebase CLI to deploy

### Steps for GitHub Pages:
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to repository Settings > Pages
4. Select source as "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Your site will be available at `https://yourusername.github.io/repository-name`

## 🎯 Performance Features

- **Lazy Loading** - Images load only when needed
- **Debounced Events** - Optimized scroll event handling
- **CSS Animations** - Hardware-accelerated animations
- **Minified Assets** - Optimized for fast loading
- **Mobile-First CSS** - Efficient responsive design

## ♿ Accessibility Features

- **Keyboard Navigation** - Full keyboard support
- **Focus Management** - Proper focus indicators
- **Screen Reader Support** - Semantic HTML and ARIA labels
- **Color Contrast** - WCAG compliant color ratios
- **Mobile Accessibility** - Touch-friendly interface

## 🔧 Advanced Customization

### Adding More Sections
To add a new section:
1. Add the HTML structure in `index.html`
2. Add corresponding styles in `style.css`
3. Update navigation menu with new link
4. Add scroll spy functionality in `main.js`

### Adding Animations
The website uses CSS animations and Intersection Observer API for scroll animations. You can add more animations by:
1. Creating CSS keyframes
2. Adding observer entries in JavaScript
3. Applying animations on scroll

### Form Integration
To make the contact form functional:
1. Set up a backend service (Node.js, PHP, etc.)
2. Or use form services like Formspree, Netlify Forms, or EmailJS
3. Update the form action attribute and JavaScript handler

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you make improvements that could benefit others, please consider submitting a pull request.

## 📞 Support

If you need help customizing this portfolio or have questions, feel free to open an issue or contact me.

---

**Happy coding! 🎉**

Built with ❤️ by Akshay Rathore
