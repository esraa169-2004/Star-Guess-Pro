# 🚀 Star Guess Pro
**Advanced Number Guessing Game with Professional Architecture**

## 📝 Description
An interactive GUI-based game where players guess a secret number.
- **Dynamic Difficulty:** Features three levels (Easy, Medium, Hard).
- **Dynamic Config:** All game settings are loaded dynamically, allowing for easy updates without changing the core code.

## 🏗️ System Architecture (Clean Code Approach)
To ensure high maintainability and follow industry standards, the project is structured into 4 specialized modules:
1. **`main.py`**: The entry point that orchestrates the application.
2. **`gui.py`**: Handles the entire User Interface and Event Binding.
3. **`game_logic.py`**: Contains the core mechanics and secret number processing.
4. **`config.py`**: A central repository for game constants and level settings.

## 📚 Technical Documentation
- **Library Deep Dive:** I have included a comprehensive **PDF Presentation** (`Star-Guess-Pro.pdf`) that explains the technical role of libraries like `Tkinter`, `Random`, and `Messagebox`.

## 🛠️ Requirements
- Python 3.x
- Tkinter (standard library)
