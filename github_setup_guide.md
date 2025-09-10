# The Rose Trivia Game - GitHub Setup Guide

## Files You'll Need

### 1. `index.html` 
Copy the entire HTML code from the trivia game artifact and save it as `index.html`

### 2. `README.md`
```markdown
# 🌹 The Rose Trivia Game

An interactive trivia game testing your knowledge about the Korean band The Rose!

## About The Game
Test your knowledge about Woosung (vocals), Dojoon (guitar), Hajoon (drums), and Jaehyeong (bass) in this beautifully designed dark-themed trivia challenge.

## Features
- ⏰ 15-second timer per question
- 🎯 10 random questions per game
- 🎨 Dark theme with musical instrument backgrounds
- 🏆 Fan ranking system (Superfan to Needs Improvement)
- ✨ Animated feedback and celebrations
- 📱 Fully responsive design

## How to Play
1. Click on a band member's name to answer each question
2. Race against the 15-second timer
3. Get your final score and fan ranking!

## Technologies Used
- HTML5
- CSS3 (with animations and gradients)
- Vanilla JavaScript
- SVG patterns for background design

## Live Demo
[Play the game here!](https://yourusername.github.io/the-rose-trivia-game/)

## The Rose Members
- 🎤 **Woosung** - Main vocalist and leader
- 🎸 **Dojoon** - Electric guitar
- 🥁 **Hajoon** - Drums  
- 🎸 **Jaehyeong** - Bass guitar

## Installation
1. Clone this repository
2. Open `index.html` in any modern web browser
3. Start playing!

---
Made with 💖 for Black Roses everywhere!
```

## GitHub Setup Steps

### Option 1: GitHub Web Interface (Easiest)
1. **Create a new repository**
   - Go to [github.com](https://github.com) and sign in
   - Click the green "New" button
   - Name it: `the-rose-trivia-game`
   - Make it public
   - Check "Add a README file"
   - Click "Create repository"

2. **Add your files**
   - Click "Add file" → "Create new file"
   - Name it `index.html`
   - Copy and paste the entire HTML code from the game
   - Scroll down and click "Commit new file"

3. **Enable GitHub Pages**
   - Go to Settings tab in your repository
   - Scroll to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)"
   - Click Save
   - Your game will be live at: `https://yourusername.github.io/the-rose-trivia-game/`

### Option 2: Using Git Commands (If you have Git installed)
```bash
# Clone your repository
git clone https://github.com/yourusername/the-rose-trivia-game.git
cd the-rose-trivia-game

# Create the HTML file
# (Copy the game code into index.html)

# Add and commit files
git add .
git commit -m "Add The Rose trivia game"
git push origin main
```

## File Structure
```
the-rose-trivia-game/
├── index.html          # The complete game
├── README.md          # Project description
└── (optional files)
```

## Optional Enhancements
You could also add:
- `style.css` - Extract CSS to separate file
- `script.js` - Extract JavaScript to separate file
- `images/` folder - If you get base64 images later
- `favicon.ico` - Custom icon for the browser tab

## Tips
- Make sure your repository name matches what you want in the URL
- GitHub Pages can take a few minutes to deploy
- The game works entirely in the browser - no server needed!
- You can customize the questions by editing the JavaScript array

---

**Ready to share your Rose trivia game with the world! 🌹**
