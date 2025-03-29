# Ava's Biggie Simulator

Ava's Biggie Simulator was created as a gift. It's a fun arcade-style game built using Python and Pygame. The goal is to eat as much food as possible while avoiding obstacles to maintain your lives. The game features an engaging graphical interface, animations, and sound effects.

## 🎮 Gameplay
### Summary
- The player controls Ava, who must collect food items while avoiding harmful exercise.
- The game begins with a **starting screen** where the player can start by pressing "Enter" or clicking the **Play** button.
- During the game, Ava moves up and down to collect food.
- Eating food increases the **score**, but consuming dangerous objects or missing food reduces **lives**.
- If lives reach zero, the player is taken to the **pause screen**, where they can restart.
  
### Score Mechanics
- The user can move along the y axis only, with the goal of collecting food items which raises the score (+1).
- If the user fails to collect food items, the score drops (-1) .
- Alternatively, there is a treadmill item which when collected also drops your score (-1). Failing to collect this does not hurt your score.


## 🛠 Features
- **Dynamic Game Screen**: Food moves from right to left, and the player must catch the correct food while avoiding obstacles.
- **Sound Effects & Music**: Background music and sound effects enhance gameplay.
- **Custom Fonts & Graphics**: Uses Pygame to load unique fonts and images.
- **Pause & Restart**: Players can retry if they lose.

## 📂 File Structure
```
Avas-Biggie-Simulator/
│── Game_class.py       # Main game logic
│── main.py             # Initializes and runs the game
│── file_Path_fn.py     # Handles file paths (not provided in upload)
│── assets/             # Stores images, fonts, and sound files
```

## 💻 Code Breakdown

### `Game_class.py`
This file defines the **Game** class, which manages game mechanics.

#### Key Methods:

- **`__init__(self, lives)`**  
  - Initializes the game state with `lives` and sets up assets.
  
- **`starting_screen(self)`**  
  - Displays the intro screen where players can press a key to start.

- **`game_screen(self)`**  
  - Handles the main gameplay loop where the player collects food.

- **`pause_screen(self)`**  
  - Displays a game-over or pause menu when the player loses.


## 🖥 Preview
![Starting Screen Screenshot](assets/game_preview.png)
![Starting Screen Screenshot](assets/game_preview.png)
![Starting Screen Screenshot](assets/game_preview.png)

## 👨‍💻 Author
- **Aidan Gutierrez** - *Developer*
