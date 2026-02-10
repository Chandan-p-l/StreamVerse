# StreamVerse Contribution Guidelines

Thank you for your interest in contributing to StreamVerse! This document provides guidelines and instructions for contributing to the project.

## 🤝 How to Contribute

### Reporting Issues

**Before submitting an issue:**
1. Check if the issue already exists in the [issue tracker](https://github.com/yourusername/streamverse/issues)
2. Try to reproduce the issue on the latest version
3. Search existing issues to avoid duplicates

**When submitting an issue, please include:**
- Clear title and description
- Steps to reproduce the issue
- Expected vs actual behavior
- Screenshots if applicable
- Browser/OS information
- Console errors (if any)

### Feature Requests

We welcome feature requests! Please:
1. Check if the feature has already been requested
2. Provide a clear description of the feature
3. Explain why it would be valuable
4. Include examples or mockups if possible

### Code Contributions

#### Getting Started

1. **Fork the repository**
   ```bash
   git clone https://github.com/yourusername/streamverse.git
   cd streamverse
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Follow the existing code style
   - Write clean, well-commented code
   - Test your changes thoroughly

4. **Commit your changes**
   ```bash
   git add .
   git commit -m "Add feature: brief description"
   ```

5. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request**

#### Pull Request Guidelines

**PR Title Format:**
```
<type>: <description>
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding tests
- `chore`: Maintenance tasks

**Example:**
```
feat: add user rating system
fix: resolve mobile navigation issue
docs: update setup guide
```

**PR Description should include:**
- What changed and why
- How to test the changes
- Screenshots (if UI changes)
- Any breaking changes
- Related issues (closes #123)

### Code Style Guide

#### HTML
- Use semantic HTML5 elements
- Maintain proper indentation (2 spaces)
- Include descriptive alt attributes for images
- Use proper meta tags for SEO

#### CSS
- Use CSS variables for theming
- Mobile-first approach with media queries
- Meaningful class names
- Comment complex styles
- Follow BEM methodology where applicable

#### JavaScript
- Use ES6+ features
- camelCase for variables and functions
- PascalCase for constructors/classes
- Descriptive function and variable names
- Comment complex logic
- Keep functions small and focused

**Example:**
```javascript
// Good
function toggleMovieInList(movieId) {
    const movie = MOVIE_DATA.find(m => m.id === movieId);
    const index = myList.findIndex(m => m.id === movieId);
    
    if (index === -1) {
        myList.push(movie);
        showToast("Added to My List");
    } else {
        myList.splice(index, 1);
        showToast("Removed from My List");
    }
    
    renderCategories();
}

// Avoid
function t(m) {
    // Unclear what this does
}
```

### Testing

**Before submitting:**
1. Test on multiple browsers (Chrome, Firefox, Safari, Edge)
2. Test on different screen sizes (mobile, tablet, desktop)
3. Verify all existing functionality still works
4. Check for console errors
5. Validate HTML/CSS

### Documentation

When adding new features:
1. Update README.md if needed
2. Add documentation in docs/ folder
3. Update CHANGELOG.md
4. Add comments in code for complex logic

## 🎯 Development Workflow

### Branch Naming Convention

```
feature/feature-name      # New features
fix/bug-name             # Bug fixes
docs/documentation-name  # Documentation
refactor/refactor-name   # Code refactoring
```

### Commit Message Guidelines

**Format:**
```
type(scope): subject

body (optional)

footer (optional)
```

**Examples:**
```
feat(movie-list): add infinite scroll

Implement infinite scrolling for movie lists to improve
user experience when browsing large collections.

Closes #123
```

```
fix(search): resolve mobile search input issue

Fixed the search input not expanding properly on mobile
devices by adjusting CSS flex properties.

Fixes #456
```

## 🚀 Getting Help

If you need help:
1. Check the [documentation](docs/)
2. Look at existing code for examples
3. Ask in GitHub issues
4. Contact the maintainers

## 📋 Review Process

All submissions require review. We aim to review PRs within 48 hours. The review process includes:

1. **Code Review**
   - Code quality and style
   - Functionality verification
   - Performance considerations
   - Security implications

2. **Testing**
   - Manual testing
   - Cross-browser compatibility
   - Responsive design verification

3. **Documentation**
   - Code comments
   - README updates
   - Changelog entries

## 🎉 Recognition

Contributors will be:
- Added to the contributors list
- Mentioned in release notes
- Given credit for their work

## 📄 License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

**Thank you for contributing to StreamVerse! 🚀**
