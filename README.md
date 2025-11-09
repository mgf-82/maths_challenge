# 🎯 Maths Challenge!

A beautiful, interactive timed mathematics practice game with progressive stages and real-time feedback. Perfect for students of all ages to sharpen their mental math skills.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## ✨ Features

### 🎮 Game Modes
- **🐣 Tiny** - Addition & Subtraction (1-6)
- **🌟 Number** - Addition & Subtraction (1-10)
- **💪 Brain** - Add/Sub, Multiplication, Fractions, Place Value
- **🍕 Fractions & Decimals** - Comprehensive fraction operations
- **🦸 Hero** - Advanced Multiplication & Division
- **🧠 Genius** - All Operations, Algebra, Powers & Roots

### 📊 Progress Tracking
- **Stage System** - Complete 5 correct answers to advance a stage
- **Visual Progress Bar** - Track progress toward the next stage in real-time
- **Streak Counter** - Track consecutive correct answers
- **Accuracy Metrics** - Real-time percentage tracking
- **Persistent Stats** - Best streak and total problems solved saved locally

### 🎨 User Experience
- **Dark Theme** - Easy on the eyes with a modern gradient background
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- **Animations** - Confetti celebrations, pulse effects, and smooth transitions
- **Sound Effects** - Optional audio feedback (can be toggled)
- **Accessibility** - ARIA labels, keyboard shortcuts, and reduced motion support

### ⌨️ Keyboard Shortcuts
- **1-4** - Select answer choice
- **Space/Enter** - Start/Resume game
- **P** - Pause/Resume
- **R** - Reset game

### ⏱️ Timer Options
Choose from 1, 2, 3, 4, or 5-minute timed challenges

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required!

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/maths-challenge.git
cd maths-challenge
```

2. Open the HTML file:
```bash
# Simply open in your browser
open maths_challenge_core_progressbar.html

# Or use a local server (optional)
python -m http.server 8000
# Then navigate to http://localhost:8000
```

That's it! The app is a single self-contained HTML file with no external dependencies.

## 🎓 How to Play

1. **Select a Mode** - Choose your difficulty and question type
2. **Set Timer** - Pick your challenge duration (1-5 minutes)
3. **Start** - Click "Start" or press Space/Enter
4. **Answer Questions** - Click answers or use number keys 1-4
5. **Complete Stages** - Get 5 correct answers to complete each stage
6. **Track Progress** - Watch your streak, accuracy, and stage count grow!

## 🏗️ Technical Details

### Built With
- **Vanilla JavaScript** - No frameworks, pure performance
- **CSS3** - Modern animations and responsive design
- **Web Audio API** - Optional sound effects
- **LocalStorage API** - Persistent statistics

### Browser Support
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

### File Structure
```
maths-challenge/
├── maths_challenge_core_progressbar.html  # Single-file app
└── README.md                              # This file
```

## 🎨 Customization

The app uses CSS custom properties for easy theming. Edit the `:root` section:

```css
:root {
  --bg: #0f1220;          /* Background */
  --panel: #161a2e;       /* Panel background */
  --ink: #e7eaf6;         /* Text color */
  --accent: #4cd27d;      /* Success color */
  --accent-2: #4ca3ff;    /* Info color */
  --danger: #ff5d6c;      /* Error color */
}
```

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

1. Report bugs or suggest features via [Issues](https://github.com/yourusername/maths-challenge/issues)
2. Submit pull requests with improvements
3. Share feedback on user experience
4. Add new question types or game modes

### Development Guidelines
- Maintain the single-file architecture
- Test on multiple browsers and devices
- Follow existing code style and conventions
- Ensure accessibility features remain intact

## 📝 License

Copyright © HRZNS  
Contact: michael@hrzns.com.au

This project is licensed under the MIT License - see below:

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

## 🎯 Roadmap

- [ ] Multiplayer mode
- [ ] Custom question sets
- [ ] Export statistics
- [ ] Leaderboards
- [ ] More question categories (geometry, word problems)
- [ ] Practice mode (no timer)
- [ ] Difficulty auto-adjustment

## 💬 Support

For questions, issues, or feedback:
- Email: michael@hrzns.com.au
- GitHub Issues: [Create an issue](https://github.com/yourusername/maths-challenge/issues)

## 🙏 Acknowledgments

- Inspired by classic mental math games
- Built with modern web standards
- Designed for accessibility and performance

---

**Made with ❤️ by HRZNS** | [michael@hrzns.com.au](mailto:michael@hrzns.com.au)
