🐍 Hex Snake
A modern twist on the classic Snake game — but with a hexagonal grid, smooth animations, and special items that change the game dynamics. Built with pure HTML5 Canvas, CSS, and JavaScript — no external libraries.

<img width="1438" height="683" alt="Screenshot 2025-08-10 at 2 51 49 PM" src="https://github.com/user-attachments/assets/e2ebb8df-0353-4532-b815-06b6d9913913" />

🎮 Features
Hexagonal movement with 6 possible directions (E, NE, NW, W, SW, SE)

Smooth snake motion with pixel interpolation

Special foods:

🍏 Normal Apple – +1 point

⭐ Golden Apple – +2 points (disappears quickly)

☠ Poison – shrink snake & -1 point

Dynamic difficulty – speed increases as you score more

Level progression – levels based on score

Shake & collapse animation on game over

Persistent high score using localStorage

Mobile-friendly controls with swipe support

🕹 How to Play
Controls (Keyboard)

Direction	Default Key:

East	Q

North-East	W

North-West	E

West	A

South-West	S

South-East	Z

➡ You can remap keys in the settings panel.

Controls (Mouse/Touch)
Use the on-screen arrow buttons

On mobile, swipe in the desired direction

⚙️ Game UI
Start / Pause buttons to control gameplay

Speed slider – change base movement speed

Score / High Score display

Level badge – shows your current level

Tips panel – helpful hints during gameplay

🧠 How It Works
Hexagonal grid: Uses axial coordinates (q, r) for positioning

Wrapping world: Exiting one edge of the map brings you back on the opposite side

Canvas rendering: All grid tiles, snake segments, and effects are drawn manually

Particles & physics: On game over, the board and snake collapse into falling pieces with dust effects

📜 Credits
Original Game Design & Code: Parth Patil

GitHub: @Alphavirusboy

Made with ❤️ using vanilla JavaScript and HTML5 Canvas

📄 License
This project is licensed under the MIT License — feel free to use, modify, and distribute.
