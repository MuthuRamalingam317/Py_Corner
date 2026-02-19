# Contributing to Py Corner

Thank you for your interest in contributing to Py Corner! 🎉

## How to Contribute

### 🐛 Reporting Bugs

1. Check if the bug has already been reported in [Issues](https://github.com/yourusername/py-corner/issues)
2. If not, create a new issue with:
   - Clear title describing the bug
   - Steps to reproduce
   - Expected vs actual behavior
   - Browser and OS information
   - Screenshots if applicable

### 💡 Suggesting Features

1. Open a new issue with the `enhancement` label
2. Describe the feature clearly
3. Explain why it would be useful
4. Include mockups or examples if possible

### 📝 Adding Questions

The easiest way to contribute! Questions are defined in `index.html`:

#### Multiple Choice Questions
Add to the appropriate category in the `QB` object:

```javascript
{
  q:"What will this code output?",
  c:"x = 5\nprint(x * 2)", // Optional code block
  o:["5","10","52","Error"], // 4 options
  a:1, // Correct answer index (0-based)
  e:"Multiplication is evaluated before print. 5 * 2 = 10.",
  d:"easy", // Difficulty: easy|medium|hard
  p:10 // XP points: 10 for easy, 15 for medium, 20 for hard
}
```

#### Code Challenge Questions
Add to the `CQ` array:

```javascript
{
  t:"Lists", // Topic
  q:"Create a list with numbers 1, 2, 3",
  h:"Use square brackets [ ] with commas.",
  ans:"my_list = [1, 2, 3]",
  va:["my_list = [1, 2, 3]","my_list=[1,2,3]"], // Valid variations
  e:"Lists use [ ]. Separate items with commas.",
  d:"easy",
  p:10
}
```

### 🎨 UI/UX Improvements

1. Fork the repository
2. Make your changes to `index.html`
3. Test in multiple browsers
4. Submit a pull request with:
   - Screenshots of before/after
   - Description of changes
   - Why the change improves UX

### 🔧 Code Contributions

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes
4. Test thoroughly
5. Commit: `git commit -m 'Add amazing feature'`
6. Push: `git push origin feature/amazing-feature`
7. Open a Pull Request

## Code Style Guidelines

- Use clear, descriptive variable names
- Add comments for complex logic
- Keep functions small and focused
- Test all changes before submitting

## Question Quality Guidelines

✅ **Good Questions**:
- Test a single concept
- Have one unambiguous correct answer
- Include a clear, educational explanation
- Are appropriate for beginners

❌ **Avoid**:
- Trick questions
- Overly complex scenarios
- Questions requiring advanced knowledge
- Ambiguous wording

## Testing Your Changes

Before submitting:

1. Open `index.html` in a browser
2. Test the specific feature you changed
3. Try different screen sizes (mobile/desktop)
4. Check console for errors (F12)
5. Verify no existing features broke

## Pull Request Process

1. Update README.md if adding features
2. Ensure your code works in modern browsers
3. Link any related issues
4. Wait for review and address feedback
5. Celebrate when merged! 🎉

## Questions?

Open an issue with the `question` label or reach out via the feedback form in the app.

## Code of Conduct

Be respectful, inclusive, and constructive. We're all here to learn and help others learn.

---

Thank you for making Py Corner better for everyone! 🐍
