# 🐍 Py Corner - Interactive Python Learning Hub

**No code to pro code — all in one corner**

Py Corner is an interactive, gamified Python learning platform that helps beginners master Python through infinite randomized questions, AI-powered explanations, and real-time feedback.

![Py Corner](https://img.shields.io/badge/Python-Learning-00b4cc?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Production-2ecc71?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-f5c518?style=for-the-badge)

## ✨ Features

### 🎯 **Core Learning Experience**
- **Infinite Random Questions** - Never run out of practice material
- **Two Question Types**: Multiple choice & code challenges
- **AI-Powered Explanations** - Get step-by-step breakdowns with live code examples
- **Retry System** - Learn from mistakes with unlimited retries
- **Instant Feedback** - Know immediately if you're right or wrong

### 🎮 **Gamification & Progress**
- **XP System** - Earn points for every correct answer
- **7 Progressive Levels** - From 🌱 Seedling to 🌟 Pro
- **Achievement System** - Unlock badges for milestones
- **Streak Tracking** - Build momentum with consecutive correct answers
- **Live Stats Dashboard** - Track accuracy, total questions, and best streak

### 🧩 **AI-Powered Learning**
- **Step-by-Step Breakdowns** - Claude AI explains every concept in plain English
- **Live Code Examples** - Each step includes runnable code you can try
- **Real-Life Analogies** - Concepts explained through everyday comparisons
- **Beginner-Friendly** - No jargon, every symbol explained

### 🎨 **Premium UX**
- **Beautiful Turquoise Theme** - Easy on the eyes, professional design
- **Smooth Animations** - Every interaction feels polished
- **Motivational Quotes** - Stay inspired while learning
- **Keyboard Shortcuts** - Press Enter to check, 'N' for next
- **Responsive Design** - Works perfectly on mobile and desktop

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)
1. Fork this repository
2. Go to Settings → Pages
3. Select `main` branch and `/root` folder
4. Click Save
5. Your site will be live at `https://yourusername.github.io/py-corner`

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/py-corner.git

# Navigate to directory
cd py-corner

# Open in browser (no build step required!)
open index.html
```

That's it! No dependencies, no build process. Just open `index.html` in any modern browser.

## 📊 How to Set Up Feedback Form

1. **Create a Google Form**:
   - Go to [Google Forms](https://forms.google.com)
   - Create a new form with fields like:
     - Email (optional)
     - Rating (1-5 stars)
     - What did you like?
     - What can be improved?
     - Feature requests

2. **Get the Form URL**:
   - Click "Send" → Link icon
   - Copy the link

3. **Update the Code**:
   - Open `index.html`
   - Find the `openFeedback()` function (around line 800)
   - Replace the `formURL` with your Google Form link

```javascript
function openFeedback(){
  const formURL='YOUR_GOOGLE_FORM_URL_HERE';
  window.open(formURL,'_blank','width=700,height=800');
}
```

## 🎓 Topics Covered

- **Syntax & Fundamentals** - Variables, operators, data types
- **Data Structures** - Lists, dictionaries, sets, tuples
- **Functions** - Definition, parameters, return values
- **Loops** - For loops, while loops, range()
- **Conditionals** - if/elif/else statements
- **Libraries** - Import statements, built-in modules

## 🛠️ Technology Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **AI Integration**: Anthropic Claude API (optional - for step-by-step breakdowns)
- **Hosting**: Any static hosting (GitHub Pages, Netlify, Vercel)
- **No Backend Required**: Fully client-side application

## 📱 Browser Support

- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Roadmap

- [ ] Add more question categories (OOP, file handling, error handling)
- [ ] Leaderboard system (localStorage-based)
- [ ] Export progress as PDF certificate
- [ ] Dark/Light theme toggle
- [ ] Multiple language support
- [ ] Voice narration for explanations
- [ ] Social sharing of achievements

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Add Questions**: Expand the question bank in `index.html`
2. **Fix Bugs**: Submit issues or pull requests
3. **Improve UX**: Suggest design improvements
4. **Add Features**: Implement items from the roadmap

### Adding Questions
Questions are stored in the `QB` (Question Bank) and `CQ` (Code Questions) objects. Format:

```javascript
{
  q:"Your question here?",
  o:["Option 1","Option 2","Option 3","Option 4"],
  a:1, // Index of correct answer (0-based)
  e:"Explanation of why this is correct.",
  d:"easy", // easy|medium|hard
  p:10 // XP points
}
```

## 📄 License

MIT License - feel free to use this project for learning, teaching, or building upon!

## 🙏 Acknowledgments

- Inspired by the Python learning community
- Built with ❤️ for beginners
- Powered by Claude AI for explanations

## 💬 Feedback & Support

- **Found a bug?** [Open an issue](https://github.com/yourusername/py-corner/issues)
- **Have suggestions?** Click the "Share Feedback" button in the app
- **Want to contribute?** Submit a pull request!

---

**Made with 🐍 and ☕ by learners, for learners**

⭐ Star this repo if you found it helpful!
