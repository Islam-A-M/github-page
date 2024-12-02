# My Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript, hosted on GitHub Pages.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive layout
- 🌓 Dark mode support
- 🎯 Smooth scroll navigation
- 💫 Scroll animations
- 📊 Project showcase section
- 📫 Contact information

## Technologies Used

- HTML5
- CSS3 (with CSS Variables and Flexbox/Grid)
- JavaScript (ES6+)
- Font Awesome Icons
- GitHub Pages for hosting

## Setup and Deployment

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   ```

2. Navigate to the project directory:
   ```bash
   cd yourusername.github.io
   ```

3. Customize the content:
   - Update the text in `index.html`
   - Modify styles in `styles.css`
   - Adjust animations in `script.js`
   - Replace project images and links
   - Update contact information

4. Deploy to GitHub Pages:
   - Push your changes to the main branch
   - Go to repository Settings > Pages
   - Select main branch as the source
   - Your site will be published at `https://yourusername.github.io`

## Customization

### Adding Projects

Add new projects by copying and modifying the project card template in `index.html`:

```html
<article class="project-card">
    <img src="path-to-image" alt="Project Name" class="project-image">
    <div class="project-content">
        <h3 class="project-title">Project Name</h3>
        <p class="project-description">Project description goes here.</p>
        <a href="#" class="project-link">View Project</a>
    </div>
</article>
```

### Modifying Colors

The color scheme can be customized by updating the CSS variables in `styles.css`:

```css
:root {
    --primary-gradient: linear-gradient(135deg, #6e8efb, #a777e3);
    --primary-color: #6e8efb;
    --secondary-color: #a777e3;
    --text-color: #333;
    --bg-color: #f5f5f5;
}
```

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

Feel free to reach out if you have any questions or suggestions:

- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourusername)
- Email: your.email@example.com
