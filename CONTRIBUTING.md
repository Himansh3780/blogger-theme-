# Contributing to Huvlio Blogger Theme

Thank you for your interest in contributing! Your improvements help make this theme better for everyone.

---

## Code of Conduct

Be respectful, inclusive, and constructive. We're here to help each other grow.

---

## How to Contribute

### 1. Report Issues

**Before creating an issue:**
- Search existing issues to avoid duplicates
- Test with latest version
- Provide clear, specific details

**Issue Template:**
```markdown
## Description
[Clear description of the issue]

## Steps to Reproduce
1. [Step 1]
2. [Step 2]
3. [Step 3]

## Expected Behavior
[What should happen]

## Actual Behavior
[What actually happens]

## Environment
- Blogger: [Yes/No]
- Browser: [Chrome/Firefox/Safari/Edge]
- OS: [Windows/Mac/Linux]
- Theme Version: [1.0.0]

## Screenshots
[If applicable]
```

### 2. Suggest Features

**Feature Request Template:**
```markdown
## Feature Description
[Clear description of feature]

## Use Case
[Why this feature is needed]

## Examples
[Example implementation or reference]

## Benefits
[How this improves the theme]
```

### 3. Submit Pull Requests

**Branch Naming:**
- `feature/feature-name` - New features
- `bugfix/bug-name` - Bug fixes
- `docs/update-name` - Documentation updates
- `refactor/component-name` - Code improvements

**Before Submitting:**
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Commit with clear messages
6. Push to your fork
7. Open pull request

**PR Checklist:**
- [ ] Tested locally
- [ ] No breaking changes
- [ ] Documentation updated
- [ ] Clear commit messages
- [ ] Follows code style
- [ ] License header included

**Commit Message Format:**
```
[Type]: Brief description

Detailed explanation if needed.
- Bullet points for multiple changes
- Reference issues: Fixes #123

Example:
feat: Add dark mode toggle

- Implements dark mode theme switcher
- Adds theme persistence to localStorage
- Updates color variables
- Fixes #42
```

**Types:**
- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation
- `style:` Code style (no logic change)
- `refactor:` Code improvement
- `test:` Tests
- `perf:` Performance

### 4. Improve Documentation

Help others by:
- Fixing typos
- Clarifying instructions
- Adding examples
- Translating content
- Creating tutorials

---

## Development Setup

### Prerequisites
- Git installed
- GitHub account
- Text editor or IDE
- Basic Blogger knowledge

### Local Setup
```bash
# Clone your fork
git clone https://github.com/YOUR-USERNAME/blogger-theme-.git

# Navigate to project
cd blogger-theme-

# Create feature branch
git checkout -b feature/your-feature-name

# Make your changes
# Test thoroughly
# Commit and push
git add .
git commit -m "feat: Your feature description"
git push origin feature/your-feature-name
```

---

## Coding Standards

### XML/HTML
- Use semantic HTML5 tags
- Proper indentation (2 spaces)
- Descriptive class/id names
- Comments for complex sections

```html
<!-- Good -->
<nav class="header-navigation" role="navigation">
  <ul class="nav-list">
    <li><a href="/">Home</a></li>
  </ul>
</nav>

<!-- Avoid -->
<div class="nav">
  <ul>
    <li><a href="/">Home</a></li>
  </ul>
</div>
```

### CSS
- BEM naming convention
- Mobile-first approach
- CSS variables for customization
- Meaningful color/spacing values

```css
/* Good */
.card {
  background: var(--bg-white);
  padding: var(--space-md);
  border-radius: 8px;
}

.card__title {
  font-size: 1.25rem;
  font-weight: 600;
}

.card--featured {
  border: 2px solid var(--primary-color);
}

/* Avoid */
.card {
  background: #fff;
  padding: 16px;
}

.cardTitle {
  font-size: 20px;
  font-weight: bold;
}
```

### JavaScript
- Use modern ES6+ syntax
- Meaningful variable names
- Comments for complex logic
- Handle errors gracefully

```javascript
// Good
const setupAnalytics = (measurementId) => {
  if (!measurementId) {
    console.error('Measurement ID is required');
    return;
  }
  
  // Initialize analytics...
};

// Avoid
function setup(id) {
  let x = id;
  // init...
}
```

---

## Testing

### Manual Testing Checklist
- [ ] Responsive design (desktop, tablet, mobile)
- [ ] Cross-browser (Chrome, Firefox, Safari, Edge)
- [ ] SEO meta tags present
- [ ] Analytics tracking
- [ ] Performance (PageSpeed)
- [ ] Accessibility (keyboard navigation, screen reader)
- [ ] Mobile touch interactions
- [ ] Links working
- [ ] Images loading
- [ ] Print styles (if applicable)

### Browser Testing
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

---

## Documentation

### When Adding Features
1. Update README.md with feature description
2. Create/update docs in `/docs` folder
3. Add code comments
4. Include examples

### Documentation Standards
- Clear, concise language
- Step-by-step instructions
- Code examples with output
- Links to relevant resources
- Appropriate headings

---

## Review Process

### What Reviewers Look For
1. **Code Quality** - Follows standards, maintainable
2. **Testing** - Thoroughly tested, no regressions
3. **Documentation** - Clear, helpful
4. **Performance** - No negative impact
5. **Security** - No vulnerabilities
6. **Compatibility** - Works across browsers/devices

### Addressing Feedback
- Read comments carefully
- Ask for clarification if needed
- Make requested changes
- Push updates to same PR
- Respond to all comments
- Re-request review

---

## Release Process

**Version Format:** `MAJOR.MINOR.PATCH` (e.g., 1.2.3)

**Changes by Type:**
- `1.0.0` → `2.0.0` = Major (breaking changes)
- `1.0.0` → `1.1.0` = Minor (new features)
- `1.0.0` → `1.0.1` = Patch (bug fixes)

**Release Steps:**
1. Update version in package/config files
2. Update CHANGELOG.md
3. Create release on GitHub
4. Tag commit with version
5. Notify users

---

## Communication

- 💬 Use GitHub issues for discussions
- 📧 Check documentation before asking
- 🤝 Be respectful and constructive
- 📝 Provide context and examples
- 🎯 Stay focused on topic

---

## Attribution

Contributors will be:
- Listed in README
- Acknowledged in release notes
- Recognized for significant contributions

---

## Questions?

1. Check [FAQ in README](../README.md)
2. Browse existing issues
3. Create new issue with "question" label
4. Check documentation in `/docs`

---

## Thank You! 🙏

Every contribution makes Huvlio better. Whether it's code, docs, bug reports, or ideas—we appreciate your effort!

Happy contributing! 🚀
