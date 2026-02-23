# 🎯 Guess The Number Game (Java Swing)

A fun interactive number guessing game built using Java Swing. The user tries to guess a randomly generated number between 1 and 100 while tracking total guesses and best score.

---

## 🚀 Features

- 🎲 Random number generation (1–100)
- 🔢 User input through text field
- 📊 Tracks total guesses
- 🏆 Best score tracking
- ❌ "Give Up" option
- 🔁 "Play Again" feature
- 🖼️ Image support (smile.png)
- 🖥️ GUI built using Java Swing

---

## 🧠 How It Works

1. A random number is generated between 0–99
2. User enters a guess
3. Program checks:
   - If guess is low → shows hint
   - If guess is high → shows hint
   - If correct → displays win message
4. Best score updates if fewer guesses are used
5. User can:
   - Click **Give Up** to reveal answer
   - Click **Play Again** to restart game

---

## 🗂️ Project Files

GuessNumber.java  
smile.png  

`GuessNumber.java` - Main game logic  
`smile.png` - Display image  

---

## 🛠️ Requirements

Make sure you have **Java JDK** installed.

Check Java version:

`java -version`

Check Java compiler:

`javac -version`

---

## ▶️ How to Run

# compile the file  
`javac GuessNumber.java`

# run the program  
`java GuessNumber`

Make sure `smile.png` is in the same folder.

---

## 🧪 Example Gameplay

- Enter a number between 1–100
- Receive hints like:
  - "50 is low, try again!!"
  - "75 is high, try again!!"
- If correct:
  - "Your guess is correct, You win!!"
- Best score updates automatically

---

## 📚 Technologies Used

`Java`  
`Swing (javax.swing)`  
`AWT (Event Handling)`  

---

## 🤝 Contributing

- Fork the repository
- Add difficulty levels
- Add timer feature
- Add sound effects
- Improve UI design
- Create a pull request

---

## 📜 License

This project is open-source and free to use for learning purposes.

---

## Author

Rehan Shaikh
