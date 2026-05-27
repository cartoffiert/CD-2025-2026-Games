#  Unity CoderDojo 2025-2026 Games

This repository contains a collection of games developed as part of the **CoderDojo** project, exploring various genres from 2D classics to 3D platformers. These projects focus on C# scripting, physics, Inheritance and advanced Unity systems.

---

##  3D Platformer

###  Game Description
A 3D platformer focusing on first-person and third person movement mechanics. This project explores 3D physics, environmental hazards, and interactive world elements. It demonstrates the use of Unity's character controller and trigger-based event systems.

| 1st Person | 3rd Person |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/68cf2ba7-26a5-4eb7-bda2-84d934ac511c" width="400"> | <img src="https://github.com/user-attachments/assets/5d2c8d6b-fae3-4848-bdbd-581fe5cf8095" width="400"> |

###  Features
* **First-Person Controller:** Smooth movement and jumping mechanics using Unity's physics engine.
* **Interactive Environment:** Features interactive objects like **Levers** (`LeverBase` / `LeverPivot`) that trigger world events.
* **Challanges:** Navigational challenges featuring **Lava** zones and **Enemy** patrol paths.
* **Checkpoint System:** Includes a logic system to save player progress and handle respawns.

###  Controls
* **Movement:** Use `W` `A` `S` `D` keys to move.
* **Jump:** Press `Space` to jump.
* **Look Around:** Use the `Mouse` to look around.
* **Pause/Unpause:** Press the `P` key.

###  [Try it yourself](https://cartoffiert.github.io/CD-2025-2026-Games/3DPlatformerWebGLBuild/)

---

##  Break Breaker 3D

###  Game Description
A 3D break braker game built using **Unity & C#**. This project focuses on 3D collision detection, ball physics, and procedural level layouts using Unity's physics engine to handle high-speed collisions.

| Main Menu | Gameplay |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/fc79cc61-589d-465d-8a4d-b828fa173f03" width="400"> | <img src="https://github.com/user-attachments/assets/9fa55a44-25e2-430d-b4fb-e9997033b88c" width="400"> |

###  Features
* **Level Selection System:** Includes a dedicated UI menu allowing players to choose between multiple levels of increasing difficulty.
* **3D Physics:** Real-time ball-to-brick physics interactions with custom bounciness.
* **Scoring & Statistics:** The game saves and displays the player's **High Score** and **Best Time** for each level.
* **Pause Menu:** Integrated pause functionality allowing players to halt gameplay and manage options mid-level.
* **Dynamic Level Design:** Increasing difficulty as the player clears layers of 3D bricks.
* **Responsive Controls:** Precise paddle movement to redirect the ball strategically.

###  Controls
* **Movement:** Use `A` and `D` keys to control the paddle position and redirect the ball.
* **Pause/Unpause:** Press the `P` key.

###  [Try it yourself](https://cartoffiert.github.io/CD-2025-2026-Games/BreakBreaker3DWebGLBuild/)

---

##  Pong Game

###  Game Description
A 2-player competitive game built using **Unity & C#**. The project focuses on learning C# scripting, collision physics, and UI management.

| Main Menu | Gameplay |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/9cb9e650-e053-43e0-8f23-561fb052e949" width="400"> | <img src="https://github.com/user-attachments/assets/6ecdff35-9d90-414d-ab72-ed4059f776a8" width="400"> |

###  Features
* **Local Multiplayer:** Play against a friend on the same keyboard.
* **Score Tracking:** Integrated UI that tracks and displays points for both players.
* **Visual Themes:** Distinct red and blue themes for player paddles.

###  Controls
* **Player 1 (Red Paddle 🟥):** `W` (Up) / `S` (Down)
* **Player 2 (Blue Paddle 🟦):** `↑` (Up Arrow) / `↓` (Down Arrow)

###  [Try it yourself](https://cartoffiert.github.io/CD-2025-2026-Games/PongGameWebGLBuild/)

---

##  Spot the Cat(s)

###  Game Description
A hidden object game where players must find cats within various scenes. This project highlights advanced architectural patterns in Unity, specifically utilizing a **custom Node System** built with **C# Inheritance** to manage game flow, audio, and visual transitions.

| Showing Cat(s) Image | Results Set |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/1d2efa6f-7960-438c-9875-1a0280743872" width="400"> | <img src="https://github.com/user-attachments/assets/b9d2d8d7-634c-4ecd-b92e-f45833eb5b47" width="400"> |

###  Features
* **Inheritance-Based Node System:** Uses a modular node arhictecture to handle sequential game logic.
* **Multiple Choice Options:** Players must choose between options A, B, C, D to identify the correct number of hidden cats.
* **Interactive Buttons:** It has a button that displays the next set of cat images after the desired option has been selected.
* **Settings Management:** A Main Menu with sliders to adjust background music and sound effects.

###  Controls
* **Start Game:** Press the `S` key to start counting cats.

###  [Try it yourself](https://cartoffiert.github.io/CD-2025-2026-Games/SpotTheCatsWebGLBuild/)
