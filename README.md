# 🎯 Guess My Number Game

A fun and interactive number guessing game built with vanilla HTML, CSS, and JavaScript. Challenge yourself to guess the secret number between 1 and 20!

## 🎮 Game Features

- **Random Number Generation**: The game generates a secret number between 1-20
- **Smart Feedback**: Get hints with "Too High" or "Too Low" messages
- **Scoring System**: Start with 100 points, lose 10 points for each wrong guess
- **High Score Tracking**: Your best score is saved locally in your browser
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Clean UI**: Modern design with dynamic color changes based on game state

## 🚀 How to Play

1. The game will generate a secret number between 1 and 20
2. Enter your guess in the input field
3. Click "Check!" to see if you're correct
4. Follow the hints to adjust your next guess
5. Try to guess the number with the highest score possible!
6. Click "Again!" to start a new game

## 🎨 Game States

- **Default**: Dark background while playing
- **Correct Guess**: Green background when you win
- **Wrong Guess**: Red background for incorrect attempts
- **Game Over**: When score reaches 0

## 📱 Mobile Responsive

The game is fully responsive and optimized for:
- **Desktop**: Full experience with large interface
- **Tablets** (480-600px): Medium-sized interface
- **Mobile** (350-480px): Compact mobile interface
- **Small Mobile** (<350px): Extra compact for small screens

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: 
  - Custom Google Fonts (Lacquer)
  - Flexbox layout
  - Media queries for responsiveness
  - CSS hover effects
- **JavaScript (ES6+)**:
  - DOM manipulation
  - Event handling
  - Local Storage for high score persistence
  - Random number generation

## 📂 Project Structure

```
guess-my-number/
├── index.html              # Main HTML structure
├── guess-my-number.css     # Styles and responsive design
├── guess-my-number.js      # Game logic and functionality
└── README.md              # Project documentation
```

## 🎯 Game Logic Overview

### Core Functions:
- `check()`: Validates user input and processes the guess
- `again()`: Resets the game for a new round

### Key Features:
- Input validation (numbers between 1-20)
- Score management and tracking
- High score persistence using localStorage
- Dynamic UI updates based on game state

## 🌟 Special Features

- **Perfect Score Achievement**: Special message for guessing correctly on first try
- **Local Storage**: High scores persist between browser sessions
- **Input Validation**: Prevents invalid inputs outside 1-20 range
- **Accessible Design**: Clear visual feedback and intuitive controls

## 🔧 Installation & Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/AvivElany/Guess-My-Number.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Guess-My-Number
   ```

3. Open `index.html` in your web browser

That's it! No build process or dependencies required.

## 🎲 Game Rules

- You have **100 points** to start
- Each wrong guess costs **10 points**
- The secret number is between **1 and 20**
- Your **high score** is automatically saved
- Game ends when you guess correctly or reach 0 points

## 🖥️ Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 👨‍💻 Developer

**Aviv Elany** - Web Developer

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements!

---

**Enjoy the game and good luck guessing! 🍀**
