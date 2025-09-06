# Sterling & Associates - CSS Flexbox Final Project

## 🎯 Project Overview

Welcome to your **CSS Flexbox Final Project**! You'll be building a professional law firm website by implementing **7 specific flexbox layouts**. This project is designed to test and demonstrate your mastery of CSS Flexbox properties and responsive design principles.

## 📋 Project Specifications

- **Project Name**: Sterling & Associates Law Firm Website
- **Technology Focus**: CSS Flexbox Layout
- **Difficulty Level**: Intermediate to Advanced
- **Estimated Time**: 2-3 hours
- **File Format**: Single HTML file with embedded CSS

## 🚀 Getting Started

### Prerequisites
- Basic understanding of HTML and CSS
- Knowledge of CSS Flexbox properties
- Code editor (VS Code, Sublime Text, Atom, etc.)
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Installation & Setup

1. **Download the Project File**
   - Save the provided HTML file as `sterling-law-project.html`
   - Ensure the file is saved with `.html` extension

2. **Open in Code Editor**
   - Launch your preferred code editor
   - Open the `sterling-law-project.html` file

3. **Preview in Browser**
   - Open the HTML file in your web browser
   - You'll see the current state of the website (broken layouts)
   - Click the "📋 View Tasks" button to see detailed instructions

## 📚 Project Structure

```
sterling-law-project.html
├── HTML Structure
│   ├── Header Navigation
│   ├── Hero Section
│   ├── Services Section
│   ├── About Section
│   ├── Team Section
│   ├── Contact Section
│   └── Footer
└── CSS Styles
    ├── Base Styles (Complete)
    ├── Flexbox Tasks (7 tasks to complete)
    └── Responsive Design (Pre-built)
```

## 🎯 Tasks Breakdown

### Task 1: Header Navigation (10 points)
**Objective**: Create a responsive navigation bar
- **Target Elements**: `.header-container`, `.nav`
- **Skills**: Basic flexbox alignment, justify-content, align-items

### Task 2: Hero Section (15 points)
**Objective**: Center hero content vertically and horizontally
- **Target Elements**: `.hero`, `.hero-content`
- **Skills**: Flex direction, centering techniques

### Task 3: Services Grid (20 points)
**Objective**: Create a responsive grid of service cards
- **Target Elements**: `.services-grid`, `.service-card`
- **Skills**: Flex wrap, responsive card layouts

### Task 4: About Section (15 points)
**Objective**: Two-column layout with text and image
- **Target Elements**: `.about-content`, `.about-text`, `.about-image`
- **Skills**: Flex basis, equal columns

### Task 5: Team Section (15 points)
**Objective**: Flexible team member grid
- **Target Elements**: `.team-grid`, `.team-member`
- **Skills**: Responsive grid with flex wrap

### Task 6: Contact Section (20 points)
**Objective**: Side-by-side contact info and form
- **Target Elements**: `.contact-content`, `.contact-info`, `.contact-form`, `.contact-item`
- **Skills**: Complex nested flexbox layouts

### Task 7: Footer (5 points)
**Objective**: Professional footer layout
- **Target Elements**: `.footer-content`, `.footer-links`
- **Skills**: Space-between alignment

## 🛠️ How to Complete Tasks

### Step-by-Step Process

1. **Locate the Task**
   - Find the CSS comment `/* TASK X: Task Description */`
   - Look for the commented-out CSS properties below it

2. **Uncomment Properties**
   - Remove the `/*` and `*/` symbols around the CSS properties
   - Example:
     ```css
     /* Before */
     /* display: flex; */
     /* justify-content: space-between; */
     
     /* After */
     display: flex;
     justify-content: space-between;
     ```

3. **Test Your Changes**
   - Save the file
   - Refresh your browser
   - Observe the layout changes

4. **Verify Responsiveness**
   - Resize your browser window
   - Ensure layouts work on different screen sizes

## 📱 Responsive Design

The project includes pre-built responsive breakpoints:
- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px

**Important**: The responsive CSS is already complete. Your job is to implement the flexbox properties that make the responsive design work properly.

## ✅ Grading Criteria

| Task | Points | Criteria |
|------|--------|----------|
| Task 1 | 10 | Header navigation properly aligned |
| Task 2 | 15 | Hero content perfectly centered |
| Task 3 | 20 | Service cards in responsive grid |
| Task 4 | 15 | About section two-column layout |
| Task 5 | 15 | Team members in flexible grid |
| Task 6 | 20 | Contact section properly laid out |
| Task 7 | 5 | Footer elements aligned |
| **Total** | **100** | |

### Bonus Points (Optional)
- **+5 points**: Add custom hover effects
- **+5 points**: Improve color scheme
- **+10 points**: Add additional sections using advanced flexbox

## 🔧 Troubleshooting

### Common Issues

**Problem**: Layout doesn't change after uncommenting CSS
- **Solution**: Make sure you removed both `/*` and `*/` symbols
- **Check**: Ensure no syntax errors in CSS

**Problem**: Mobile layout is broken
- **Solution**: Don't modify the `@media` queries - they're already complete
- **Check**: Ensure all flexbox properties are properly uncommented

**Problem**: Cards/items not aligning properly
- **Solution**: Double-check `align-items`, `justify-content`, and `flex` properties
- **Check**: Verify you uncommented ALL required properties for each task

### Validation
- Use browser Developer Tools (F12) to inspect elements
- Check for CSS syntax errors in the Console
- Validate your HTML using W3C Markup Validator

## 📖 Learning Objectives

By completing this project, you will demonstrate:

1. **Flexbox Fundamentals**
   - `display: flex`
   - `flex-direction`
   - `justify-content`
   - `align-items`

2. **Responsive Layouts**
   - `flex-wrap`
   - `flex: 1`
   - `min-width` and `max-width`

3. **Advanced Flexbox**
   - Nested flex containers
   - Complex alignment scenarios
   - Real-world layout challenges

## 📚 Resources

### Flexbox References
- [MDN Flexbox Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout)
- [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Flexbox Froggy Game](https://flexboxfroggy.com/)

### Testing Tools
- Browser Developer Tools (F12)
- [Am I Responsive?](http://ami.responsivedesign.is/)
- [Responsive Design Checker](https://responsivedesignchecker.com/)

## 🎉 Submission Guidelines

### Before Submission
- [ ] All 7 tasks completed
- [ ] Website displays properly on desktop
- [ ] Website displays properly on mobile
- [ ] No CSS syntax errors
- [ ] All sections render correctly

### Submission Format
- Submit the completed `sterling-law-project.html` file
- Include a brief comment at the top of your CSS with your name and completion date
- Optional: Include screenshots of desktop and mobile views

### Example Header Comment
```css
/*
Student Name: [Your Name]
Project: Sterling & Associates Flexbox Final Project
Date Completed: [Date]
Tasks Completed: 1, 2, 3, 4, 5, 6, 7
Bonus Features: [List any bonus features added]
*/
```

## 🏆 Success Tips

1. **Work Incrementally**: Complete one task at a time
2. **Test Frequently**: Save and refresh after each task
3. **Use Developer Tools**: Inspect elements to understand layouts
4. **Read Comments**: Task instructions are detailed in the CSS comments
5. **Ask for Help**: Don't hesitate to ask questions if stuck

## 📞 Support

If you encounter issues or have questions:
- Review the in-browser task instructions (📋 View Tasks button)
- Check the troubleshooting section above
- Consult the provided flexbox resources
- Ask your instructor during office hours

---

**Good luck with your project! 🚀**

*Remember: This project simulates real-world web development. Take your time, test thoroughly, and be proud of your professional law firm website!*