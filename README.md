# 🪂 Hangman Game in C++

A classic two-player Hangman game implemented in C++.

## 🎮 How to Play
1. **Player 1** enters a secret word and provides a hint.
2. **Player 2** tries to guess the word letter by letter.
3. The game provides visual feedback:
   - ✅ Correct guesses reveal letters.
   - ❌ Incorrect guesses reduce the number of attempts.
4. The player wins if they guess the word before running out of attempts.

## 🛠 Features
- Displays a **hangman drawing** based on incorrect attempts.
- Provides a **hint** to assist Player 2.
- Prevents repeated guesses.
- Supports **uppercase conversion** for consistency.

## 📌 Requirements
- C++ Compiler (e.g., g++ or MSVC)
- Windows (uses `windows.h` and `system("cls")`)

## ▶️ Compile & Run
```bash
g++ Hangman.cpp -o Hangman
Hangman.exe
