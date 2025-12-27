# 🎮 Color Memory Match Game

A beautiful and interactive memory matching game built with HTML, Tailwind CSS, and vanilla JavaScript.

## 📝 Description

Color Memory Match is a classic memory game where players flip cards to find matching pairs of colorful emojis. The game features a stunning gradient interface with smooth animations and keeps track of your progress as you play.

## ✨ Features

- **8 Matching Pairs**: Find all 8 pairs of colored emoji cards
- **Move Counter**: Track how many moves it takes you to complete the game
- **Match Tracker**: Real-time display of matched pairs (0/8 to 8/8)
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Beautiful UI**: Gradient backgrounds with glass-morphism effects
- **Smooth Animations**: Card flip animations and hover effects
- **Win Celebration**: Animated victory message when you complete the game
- **Reset Functionality**: Start a new game anytime with shuffled cards

## 🎯 How to Play

1. **Start the Game**: Cards are randomly shuffled and placed face-down on the board
2. **Flip Cards**: Click on any card to reveal the emoji underneath
3. **Find Matches**: Click a second card to try and find a matching emoji
4. **Match Found**: If the emojis match, the cards stay flipped and become semi-transparent
5. **No Match**: If the emojis don't match, both cards flip back face-down after a brief delay
6. **Win the Game**: Match all 8 pairs to win and see your final move count
7. **Play Again**: Click the "New Game" button to shuffle and start over

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Structure and markup
- **Tailwind CSS**: Styling and responsive design (loaded via CDN)
- **JavaScript (ES6)**: Game logic and interactivity

### File Structure
```
memory-match-game.html (single file containing everything)
├── HTML structure
├── Tailwind CSS styling
└── JavaScript game logic
```

### Key Components

**Game Board**: 4x4 grid containing 16 cards (8 pairs)

**Card States**:
- Face-down (default)
- Flipped (showing emoji)
- Matched (permanently revealed)

**Game Mechanics**:
- Cards are shuffled using the Fisher-Yates algorithm
- Maximum 2 cards can be flipped at a time
- 800ms delay before checking matches
- Move counter increments with each pair attempt

## 🚀 Getting Started

### Installation

1. Download the `memory-match-game.html` file
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. No additional installation or dependencies required!

### Running the Game

Simply double-click the HTML file or open it in your browser:
```
file:///path/to/memory-match-game.html
```

Or serve it using a local web server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
```

## 🎨 Customization

You can easily customize the game by modifying these variables in the JavaScript section:

```javascript
// Change the emojis
const colors = ['🔴', '🟢', '🔵', '🟡', '🟣', '🟠', '⚫', '⚪'];

// Adjust grid size (modify CSS grid-cols-4 and add/remove pairs)
```

### Color Scheme
The game uses a purple-blue gradient theme. To change colors, modify the Tailwind classes in the `<body>` and card elements.

## 📱 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

Requires a modern browser with ES6 JavaScript support.

## 🎓 Learning Outcomes

This project demonstrates:
- DOM manipulation
- Event handling
- Array shuffling algorithms
- State management
- CSS animations and transitions
- Responsive design with Tailwind CSS
- Game logic implementation

## 🤝 Contributing

Feel free to fork and customize this game! Some ideas for enhancements:
- Add difficulty levels (more cards)
- Implement a timer
- Add sound effects
- Create a high score leaderboard
- Add different themes
- Implement multiplayer mode

## 📄 License

This project is open source and available for personal and educational use.

## 🙋 Support

If you encounter any issues or have questions, feel free to reach out or open an issue.

---

**Enjoy the game and have fun matching! 🎉**