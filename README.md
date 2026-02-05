♟️ Chess AI - AI-Powered Browser Chess Game

> Play chess against an intelligent AI opponent directly in your browser. Built with pure JavaScript and AI-assisted development.

[![Live Demo](https://img.shields.io/badge/demo-online-green.svg)](https://www.vibecodegames.org/chess/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[🎮 **Play Now**](https://www.vibecodegames.org/chess/) | [📝 Report Bug](https://github.com/gritsenko31/chess-ai/issues)

## 📖 About

Chess AI is a fully functional browser-based chess game featuring an intelligent AI opponent. The game implements all standard chess rules including castling, en passant, pawn promotion, and check/checkmate detection. Perfect for practicing chess tactics or enjoying a quick game anytime.

## ✨ Features

- 🤖 **Smart AI Opponent** - Challenging computer player with strategic move selection
- ♟️ **Complete Chess Rules** - All official FIDE chess rules implemented
- 🎯 **Move Validation** - Real-time legal move highlighting and validation
- 👑 **Special Moves** - Castling, en passant, and pawn promotion supported
- 🎨 **Clean Interface** - Intuitive drag-and-drop or click-to-move controls
- 📱 **Responsive Design** - Play on desktop, tablet, or mobile
- ⚡ **Zero Installation** - Runs entirely in the browser, no downloads needed
- 🔄 **Game History** - Move history tracking with undo functionality

## 🎮 How to Play

1. **White pieces** always start first
2. **Click** on a piece to see available moves (highlighted squares)
3. **Click** on a highlighted square to move your piece
4. The **AI automatically responds** with its move
5. Continue playing until **checkmate**, **stalemate**, or **draw**

### Controls

- **Left Click** - Select and move pieces
- **Drag & Drop** - Alternative move method
- **New Game Button** - Start a fresh game
- **Undo Button** - Take back your last move (if available)

## 🛠️ Technologies

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Chess Logic:** Custom implementation with minimax/alpha-beta pruning
- **UI Framework:** None (pure JavaScript for performance)
- **Deployment:** Static hosting on Netlify/Vercel
- **Development:** AI-assisted coding (vibe coding)

## 🚀 Quick Start

### Play Online

Visit [vibecodegames.org/chess](https://www.vibecodegames.org/chess/) to play instantly.

### Run Locally

```bash
# Clone the repository
git clone https://github.com/gritsenko31/chess-ai.git

# Navigate to project directory
cd chess-ai

# Open in browser (no build required)
# Option 1: Double-click index.html
# Option 2: Use a local server
python -m http.server 8000
# Then visit http://localhost:8000
📂 Project Structure
text
chess-ai/
├── index.html          # Main HTML file
├── style.css           # Styling and layout
├── chess.js            # Core chess game logic
├── ai.js               # AI opponent algorithm
├── board.js            # Board rendering and UI
├── /assets
│   ├── /pieces         # Chess piece images
│   └── /sounds         # Move and capture sounds (optional)
└── README.md
🎯 AI Algorithm
The AI opponent uses a minimax algorithm with alpha-beta pruning to evaluate positions and select optimal moves. The AI considers:

Material balance (piece values)

Positional advantages

King safety

Piece activity and mobility

Tactical opportunities (forks, pins, skewers)

The search depth can be adjusted for difficulty levels.

🧩 Chess Rules Implemented
✅ Standard piece movements (Pawn, Rook, Knight, Bishop, Queen, King)

✅ Castling (kingside and queenside)

✅ En passant captures

✅ Pawn promotion (to Queen, Rook, Bishop, or Knight)

✅ Check and checkmate detection

✅ Stalemate and draw conditions

✅ Threefold repetition (optional)

✅ Fifty-move rule (optional)

🔧 Customization
Want to modify the game? Here are some easy tweaks:

javascript
// In ai.js - Adjust AI difficulty
const AI_DEPTH = 3; // Increase for harder AI (2-4 recommended)

// In style.css - Change board theme
.light-square { background: #f0d9b5; }
.dark-square { background: #b58863; }
🤝 Contributing
Contributions are welcome! Whether it's bug fixes, new features, or UI improvements:

Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

Ideas for Contributions
Add difficulty level selector

Implement time controls (blitz, rapid, classical)

Add opening book for AI

Create different board themes

Add move notation display (PGN format)

Implement multiplayer mode

🐛 Known Issues
AI may take 2-3 seconds for complex positions (optimization in progress)

Mobile touch interactions can be improved

No chess clock/timer currently implemented


👤 Author
Vibe Code Games

🌐 Website: vibecodegames.org

💼 GitHub: @gritsenko31

🎮 More Games: 23+ Browser Games

🌟 Support
If you enjoyed this game:

⭐ Star this repository

🎮 Try my other games at vibecodegames.org

🐛 Report bugs or suggest features via Issues

🙏 Acknowledgments
Chess piece designs inspired by traditional Staunton style

AI algorithm based on minimax with alpha-beta pruning

Built using AI-assisted development (Claude, ChatGPT)

Part of the vibe coding movement

Made with ♟️ and AI | Play More Games | © 2026
