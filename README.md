# ♟️ JavaScript Chess Game

A simple interactive **Chess Game built using HTML, CSS, and JavaScript**. This project creates an 8×8 chessboard where players can move chess pieces, capture opponent pieces, and play by taking turns.

## 🎯 Features

* ♟️ Interactive 8×8 chessboard
* ⚪ White and Black chess pieces
* 🔄 Turn-based gameplay
* 🎯 Highlights possible moves
* ⚔️ Capturing opponent pieces
* 👑 Support for King, Queen, Rook, Bishop, Knight, and Pawn movements
* 🏰 Castling support for the King and Rook
* ✨ Animated move highlighting
* 🖱️ Click-based piece selection and movement
* 📱 Simple responsive board layout

## 🛠️ Technologies Used

* **HTML5** – Creates the chessboard structure and game interface
* **CSS3** – Provides board styling, animations, hover effects, and move highlighting
* **JavaScript** – Handles chess pieces, movement logic, captures, turns, and game interactions
* **jQuery** – Used for DOM manipulation and click events

The HTML creates the chessboard using individual game cells and includes the JavaScript file for game functionality.

## 📂 Project Structure

```text
JavaScript-Chess-Game/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🎮 How to Play

1. Open `index.html` in a web browser.
2. The game starts with **White's turn**.
3. Click on a chess piece to select it.
4. Available movement positions are highlighted.
5. Click on a valid highlighted cell to move the piece.
6. Players take turns between White and Black.
7. Opponent pieces can be captured by moving onto their position.

The JavaScript maintains the current turn and switches between White and Black after a move.

## ♜ Chess Movement

The game contains movement logic for:

* King
* Queen
* Bishop
* Knight
* Rook
* Pawn

Different movement calculations are implemented for each piece, including straight, diagonal, and knight movements.

## ⚔️ Capturing

When a piece captures an opponent's piece, the target cell is updated with the attacking piece and the captured piece is marked as captured.

## 🏰 Castling

The project also includes basic castling functionality for both White and Black. When the required conditions are satisfied, the King and corresponding Rook are moved to their castling positions.

## ✨ Styling & Animation

CSS is used to create:

* Chessboard styling
* Hover effects
* Move highlighting
* Neon text effects
* Shake animations
* Turn-change highlighting

The board cells have interactive hover effects and highlighted movement states.

## 🚀 How to Run

No installation or build tools are required.

Simply:

```text
1. Download or clone the repository
2. Open index.html
3. Start playing chess in your browser
```

## 📚 Learning Outcomes

This project helped demonstrate practical concepts such as:

* DOM manipulation
* JavaScript objects and functions
* Event handling
* Conditional logic
* Array operations
* Game-state management
* CSS animations
* Interactive web development

## 🔮 Future Improvements

Possible future enhancements include:

* Check and checkmate detection
* Pawn promotion
* En passant
* Undo/redo moves
* Restart game button
* Move history
* Chess timer
* Player score tracking
* Improved mobile responsiveness
* AI opponent

## 👩‍💻 Author

**Mythili K**

A beginner-friendly web development project created to practice **HTML, CSS, JavaScript, and interactive game development**.
