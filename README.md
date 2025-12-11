# HTML-CSS-exercises

A comprehensive collection of HTML and CSS exercises designed to strengthen foundational web development skills, from basic markup to advanced styling techniques.

## 📋 Overview

This repository contains structured exercises for learning HTML5 and CSS3. Whether you're a beginner learning web fundamentals or an intermediate developer refining your skills, these exercises provide hands-on practice with real-world scenarios and best practices.

### Key Learning Areas:
- **HTML Fundamentals**: Semantic markup, forms, accessibility
- **CSS Styling**: Flexbox, Grid, Responsive Design
- **Web Standards**: Best practices and modern conventions
- **Interactive Elements**: Forms, transitions, animations

## 📁 Project Structure

```
HTML-CSS-exercises/
├── CV.HTML                 # Curriculum Vitae HTML structure
├── CV.css                  # CV styling with resume layout
├── resume.html             # Alternative resume template
├── resume.css              # Resume styling and animations
├── README.md               # Project documentation
└── [Additional exercises]  # Various HTML/CSS challenges
```

## 🎯 Exercise Categories

### Basic HTML Markup
- Document structure and semantic elements
- Form creation and input types
- Accessibility attributes and ARIA labels
- Meta tags and SEO fundamentals

### CSS Styling Techniques
- Selectors and specificity
- Box model and spacing
- Flexbox layouts for responsive design
- CSS Grid for complex layouts
- Typography and font management

### Advanced Concepts
- CSS animations and transitions
- Media queries for responsive design
- CSS custom properties (variables)
- Pseudo-elements and pseudo-classes
- Transform and filter effects

### Practical Projects
- Professional CV/Resume layout
- Responsive navigation menus
- Card-based layouts
- Form styling and validation
- Typography showcases

## 🚀 Getting Started

### Prerequisites
- Basic understanding of HTML and CSS
- A code editor (VS Code recommended)
- A modern web browser
- Git for version control

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ritvikvr/HTML-CSS-exercises.git
cd HTML-CSS-exercises
```

2. Open files in your preferred code editor:
```bash
code .
```

3. View exercises in your browser:
   - Right-click on any `.html` file
   - Select "Open with" → Browser
   - Or use a local server: `python -m http.server 8000`

## 💡 How to Use

1. **Start with Basic Exercises**: Begin with fundamental HTML structure and simple CSS
2. **Progressive Difficulty**: Move to more complex layouts and styling
3. **Modify and Experiment**: Edit the CSS and HTML to understand how changes affect the output
4. **View in Browser**: Regularly check your progress in the browser
5. **Compare Solutions**: Review different approaches to the same problem

## 📖 Exercise Breakdown

### CV/Resume Exercises
- Create a professional CV layout
- Style a resume with modern design principles
- Practice typography and spacing
- Learn about print-friendly CSS

**Skills Practiced**:
- Semantic HTML structure
- CSS Grid and Flexbox layouts
- Typography hierarchy
- Color schemes and contrast
- Responsive design principles

### Layout Challenges
- Two-column layouts
- Multi-column designs
- Centered layouts
- Fixed and sticky positioning

### Styling Exercises
- Button designs and states
- Card components
- Navigation bars
- Form styling

## 🛠️ Technologies & Tools

| Technology | Purpose |
|------------|----------|
| HTML5 | Semantic markup and structure |
| CSS3 | Styling and layout |
| Flexbox | Flexible box layouts |
| CSS Grid | Two-dimensional layouts |
| Media Queries | Responsive design |
| CSS Variables | Dynamic styling |
| Transform | Element transformations |
| Animations | Motion and transitions |

## 🎓 Learning Objectives

After completing these exercises, you will be able to:

- Write semantic and accessible HTML
- Create responsive layouts with Flexbox and Grid
- Style elements using modern CSS techniques
- Implement animations and transitions
- Build professional-looking web pages
- Debug layout and styling issues
- Follow web development best practices
- Optimize CSS for performance

## 💻 Code Examples

### Flexbox Layout Example
```html
<div class="container">
  <header>Header</header>
  <main>Main Content</main>
  <footer>Footer</footer>
</div>
```

```css
.container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

main {
  flex: 1;
}
```

### CSS Grid Example
```css
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}
```

### Responsive Design Example
```css
@media (max-width: 768px) {
  .container {
    flex-direction: column;
  }
  
  .sidebar {
    width: 100%;
  }
}
```

## 📚 Best Practices Covered

1. **Semantic HTML**
   - Use appropriate HTML5 elements
   - Improve accessibility and SEO
   - Better code readability

2. **CSS Organization**
   - Mobile-first approach
   - Logical property grouping
   - Comment documentation

3. **Responsive Design**
   - Flexible layouts
   - Media queries strategy
   - Mobile-first methodology

4. **Performance**
   - Minimize CSS file size
   - Efficient selectors
   - Lazy loading principles

5. **Accessibility**
   - Color contrast ratios
   - Focus states for keyboard navigation
   - ARIA labels and roles
   - Semantic structure

## 🔍 Common Challenges & Solutions

### Challenge: Centering Elements
```css
/* Using Flexbox */
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}

/* Using Grid */
.container {
  display: grid;
  place-items: center;
}
```

### Challenge: Responsive Images
```css
img {
  max-width: 100%;
  height: auto;
  display: block;
}
```

### Challenge: Sticky Headers
```css
header {
  position: sticky;
  top: 0;
  z-index: 100;
}
```

## 🚦 Progress Tracking

Maintain a checklist of completed exercises:

- [ ] HTML Structure Fundamentals
- [ ] CSS Selectors and Specificity
- [ ] Box Model Exercises
- [ ] Flexbox Layouts
- [ ] CSS Grid Layouts
- [ ] Responsive Design
- [ ] Forms and Input Styling
- [ ] Animations and Transitions
- [ ] CV/Resume Project
- [ ] Complete Portfolio Site

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/new-exercise`
3. Commit changes: `git commit -m 'Add new exercise'`
4. Push to branch: `git push origin feature/new-exercise`
5. Submit a pull request

Please follow these guidelines:
- Use semantic HTML
- Write clean, commented CSS
- Ensure responsive design
- Include documentation
- Test across browsers

## 📋 Exercise Checklist

### Beginner Level
- [ ] Create a basic HTML document structure
- [ ] Style text with CSS (colors, fonts, sizes)
- [ ] Create a simple navigation menu
- [ ] Build a basic form
- [ ] Style buttons and links

### Intermediate Level
- [ ] Create multi-column layouts with Flexbox
- [ ] Implement CSS Grid layouts
- [ ] Build responsive navigation
- [ ] Create card components
- [ ] Implement form validation styles

### Advanced Level
- [ ] Complex grid layouts
- [ ] CSS animations and transitions
- [ ] Advanced responsive techniques
- [ ] CSS custom properties and theming
- [ ] Performance optimization

## 🐛 Troubleshooting

### CSS Not Applying
- Check CSS file is linked in HTML
- Verify selector specificity
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Check for typos in class/ID names

### Layout Breaking on Mobile
- Add viewport meta tag: `<meta name="viewport" content="width=device-width, initial-scale=1">`
- Test media queries
- Check for fixed widths
- Use relative units (%, em, rem)

### Flexbox Not Working as Expected
- Ensure parent has `display: flex`
- Check flex-direction
- Verify justify-content and align-items values
- Check child element width constraints

## 📚 Resources for Further Learning

- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS Tricks - Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Web.dev Learning Paths](https://web.dev/learn/)
- [FreeCodeCamp Responsive Design](https://www.freecodecamp.org/)

## 🎯 Next Steps

1. **Master HTML Fundamentals**
   - Complete all basic HTML exercises
   - Learn semantic HTML5 elements
   - Practice forms and accessibility

2. **Build CSS Skills**
   - Practice selectors and cascading
   - Master layout techniques
   - Understand the box model deeply

3. **Create Responsive Designs**
   - Learn mobile-first approach
   - Master media queries
   - Build flexible layouts

4. **Build Projects**
   - Create personal portfolio
   - Build practical websites
   - Practice real-world scenarios

5. **Explore Advanced Topics**
   - CSS preprocessing (SCSS/Less)
   - CSS frameworks (Bootstrap, Tailwind)
   - JavaScript integration

## 📞 Support

For questions or issues:
- Open a GitHub issue
- Check existing issues for solutions
- Provide code examples when reporting bugs
- Be specific about the problem and browser used

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

```
MIT License

Copyright (c) 2024 Ritvik Verma

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

## 👤 Author

**Ritvik Verma** (@ritvikvr)
- Computer Science Engineering Student specializing in AI & Data Science
- Passionate about Web Development, Full-Stack Development, and Clean Code
- GitHub: [ritvikvr](https://github.com/ritvikvr)
- Interested in: Web Development, UI/UX Design, Frontend Architecture, Responsive Design

---

**Happy Coding! 🚀**

Remember: The best way to learn HTML and CSS is by doing. Start with the basics, experiment, and gradually work your way up to more complex projects. Happy styling!
