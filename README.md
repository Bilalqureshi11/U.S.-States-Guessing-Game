# 🇺🇸 U.S. States Guessing Game (Python)

This is an interactive Python game where players guess the names of U.S. states.
Correctly guessed states are displayed on a blank U.S. map using Turtle graphics.

---

## 🎮 How the Game Works

- A blank map of the United States is displayed.
- The player types the name of a U.S. state.
- If the guess is correct:
  - The state name appears at the correct location on the map.
- The score updates after every correct guess.
- If the player types **"Exit"**:
  - The game ends.
  - A CSV file (`states_to_learn.csv`) is created containing the states not guessed.

---

## 🛠️ Technologies Used

- Python
- Turtle Graphics
- Pandas
- CSV file handling

---

## 📂 Project Files

- `main.py` → Main game logic  
- `50_states.csv` → State names with x, y coordinates  
- `blank_states_img.gif` → U.S. map image  
- `states_to_learn.csv` → Generated file for missed states  

---

   ```bash
   git clone https://github.com/your-username/US-States-Game-Python.git
