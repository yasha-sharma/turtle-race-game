# turtle-race-game
A classic Turtle Race Game built with Python's Turtle graphics.
# 🏁 Python Turtle Racing Game

A simple, fun, and colorful racing game built using Python's built-in **Turtle graphics** library. Users place a bet on which color turtle they think will win the race across the screen!

## 🎮 How to Play

1.  When the script starts, a prompt will appear asking you to **"Make a bet"**.
2.  Enter the color of the turtle you think will win (e.g., `red`, `blue`, `green`, `yellow`, `purple`, or `orange`).
3.  Watch the race unfold! Each turtle moves a random distance on every iteration.
4.  The game announces whether you **"won"** or **"lost"** based on your prediction.

## 🛠️ Requirements & Setup

This project uses only the standard Python libraries, making it very easy to run.

1.  **Clone the repository:**
    ```bash
    git clone [Your GitHub Repo URL]
    cd python-turtle-race
    ```
2.  **Run the game:**
    ```bash
    python main.py
    ```

## ✨ Features and Code Highlights

* **Interactive Input:** Uses `screen.textinput` to get the user's bet.
* **Dynamic Turtles:** Creates 6 different colored turtles, all starting at the left side of the screen.
* **Race Logic:** Uses a `while is_race_on:` loop to move the turtles randomly until one of them crosses the finish line (`xcor() > 230`).
* **Bet Results:** Compares the winning turtle's color with the user's guess to determine the winner.
