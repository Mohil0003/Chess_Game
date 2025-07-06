# Javascript Chess Game by Mohil

A simple, interactive chess game built with HTML, CSS, JavaScript, and jQuery. Play classic chess in your browser with a clean interface and basic move validation.

---

## Features

- **Full Chess Board:** 8x8 grid with labeled rows and columns.
- **All Chess Pieces:** King, Queen, Rook, Bishop, Knight, Pawn for both white and black.
- **Move Validation:** Only legal moves are allowed for each piece.
- **Turn Indicator:** Shows whose turn it is ("White's Turn" or "Black's Turn").
- **Highlighting:** Possible moves are highlighted for the selected piece.
- **Capture Logic:** Capturing works for all pieces.
- **Game Over Detection:** Game ends and shows a message when a king is captured.
- **Reset Game:** "Reset Game" button to restart the board at any time.
- **Responsive Layout:** Board and controls are centered and styled for clarity.

---

## How to Use

1. **Open `index.html` in your browser.**
2. Click on a piece to see its possible moves.
3. Click a highlighted square to move the piece.
4. The turn will automatically switch between White and Black.
5. If a king is captured, an alert will show the winner and the game will reset.
6. Click the "Reset Game" button at any time to restart the game.

---

## Project Structure

```
/source code/
  ├── index.html      # Main HTML file with chess board and controls
  ├── style.css       # CSS for board, pieces, and layout
  └── script.js       # All chess logic and interactivity
```

---

## Customization

- You can change the board colors and piece styles in `style.css`.
- All chess logic is in `script.js` if you want to add features like check/checkmate, move history, or AI.

---

## Requirements

- Modern web browser (Chrome, Firefox, Edge, etc.)
- No installation needed; just open `index.html`.

---

## Credits

- Developed by Mohil Parmar.
- Uses [jQuery](https://jquery.com/) for DOM manipulation.

---

## License

This project is licensed under the MIT License.

