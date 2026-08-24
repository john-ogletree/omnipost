# Contributing to OmniPost

First off, thank you for considering contributing to OmniPost! It's people like you that make this tool better for everyone. 🎉

## Code of Conduct

By participating in this project, you are expected to uphold my [Code of Conduct](CODE_OF_CONDUCT.md). Please report unacceptable behavior to me directly.

## How Can You Contribute?

### 🐛 Reporting Bugs

Before creating bug reports, please check the existing issues to avoid duplicates. When you're creating a bug report, include as many details as possible:

- **Use a clear and descriptive title** for the issue
- **Describe the exact steps to reproduce the problem**
- **Describe the behavior you observed** and what you expected to see
- **Include screenshots** if possible
- **Include your browser name and version**
- **Include the device you're using** (desktop, tablet, mobile)

### 💡 Suggesting Enhancements

Have an idea to make OmniPost better? I'd love to hear it! Enhancement suggestions are tracked as issues. When creating an enhancement suggestion, please include:

- **A clear and descriptive title**
- **A detailed description of the proposed functionality**
- **Explain why this enhancement would be useful** to most users
- **Include mockups or examples** if applicable

### 🔧 Pull Requests

Here's the process for submitting a pull request:

1. **Fork the repository** to your own GitHub account
2. **Create a new branch** for your feature/fix
3. **Make your changes** following the project's coding style
4. **Test your changes** thoroughly
5. **Commit your changes** with a clear, descriptive commit message
6. **Push to your fork** and submit a pull request
7. **Wait for review** - I'll review your PR and may request changes

## Development Setup

### Prerequisites

- A modern web browser
- A text editor (VS Code recommended)
- Basic knowledge of HTML, CSS, and JavaScript

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/john-ogletree/omnipost.git
cd omnipost
```

2. Open `index.html` in your browser
   - You can use Live Server in VS Code for hot-reloading
   - Or simply open the file directly

3. Make your changes and test them immediately

4. Ensure all existing features still work

### Project Structure

```
omnipost/
├── index.html          # Main application
├── style.css           # External styles
├── README.md           # Project documentation
├── CONTRIBUTING.md     # This file
└── CODE_OF_CONDUCT.md  # Code of conduct
```

## Coding Guidelines

### HTML

- Use semantic HTML5 elements where possible
- Keep class names descriptive and consistent
- Use Tailwind CSS classes for styling
- Maintain proper indentation (2 spaces)

### CSS

- Keep styles in `style.css` for external styles
- Use Tailwind for most styling
- Only add custom CSS when Tailwind can't achieve the desired effect
- Use meaningful class names

### JavaScript

- Use vanilla JavaScript (no frameworks)
- Keep functions focused and single-purpose
- Use descriptive variable and function names
- Comment complex logic
- Maintain consistent indentation (2 spaces)

### Commit Messages

Use clear and descriptive commit messages:

```
feat: Add new feature
fix: Fix bug with canvas rendering
docs: Update README documentation
style: Improve CSS styling
refactor: Clean up code structure
test: Add tests for new feature
chore: Update dependencies
```

## Feature Ideas I'd Love Help With

Here are some areas where contributions are especially welcome:

- **Font Selection**: Add custom font integration
- **Background Images**: Allow users to upload custom backgrounds
- **Export Options**: Support for different aspect ratios (1:1, 4:5, 16:9)
- **Quote History**: Save and manage previously used quotes
- **Accessibility**: Improve keyboard navigation and screen reader support
- **Performance**: Optimize canvas rendering
- **Documentation**: Improve and expand documentation

## Testing

Before submitting a pull request, please test:

1. All core functionality works
2. Export feature generates images correctly
3. Color pickers update the canvas in real-time
4. Templates apply correctly
5. Responsive design works on different screen sizes
6. No console errors appear

## Style Guide

### Color Palette

The project uses a dark theme with these primary colors:

- Background: `#04060a`, `#0d111c`
- Text: `#ffffff`, `#94a3b8`, `#64748b`
- Accent: `#818cf8` (Indigo), `#2563eb` (Blue)
- Surface: `#1e293b`, `#0f172a`

### Typography

- Font family: `system-ui, -apple-system, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif`
- Use Tailwind's font size utilities

## Recognition

Contributors will be recognized in the project's README. I appreciate all contributions, big or small!

## Questions?

If you have any questions about contributing, please:

- Open an issue
- Contact me on GitHub
- Visit [john-ogletree.github.io](https://john-ogletree.github.io)

---

**Thank you for contributing to OmniPost!** 🙏

Your time and effort help make this tool better for everyone. Every contribution, no matter how small, is valuable.

---

*Last Updated: August 2026*
```
