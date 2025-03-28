# Pothole Jumper 🚗💨

A simple yet addictive endless runner game built entirely with the [P5.js](https://p5js.org/) library. Test your reflexes as you control a red ball, jumping over hazardous potholes appearing on a continuously moving platform. Collect coins for bonus points and see how long you can survive!

**(Optional but Recommended: Add a Screenshot or GIF Here!)**

![Gameplay Screenshot](placeholder.png)
*Replace `placeholder.png` with the path to an actual screenshot or GIF of your game. You can create a GIF using tools like LiceCap or ScreenToGif.*

---

## How to Play

1.  **Enter Nickname:** Type your desired nickname on the start screen.
2.  **Start:** Click the "Start Game" button.
3.  **Jump:** Press the `SPACEBAR` to make the red ball jump over potholes.
4.  **Pause/Resume:** Press the `P` key or click the pause button ( || / ▶️ ) in the top-right corner to pause or resume the game.
5.  **Survive:** Avoid falling into the black potholes.
6.  **Score:** Your score increases over time, for each pothole successfully jumped over (+5), and for each coin collected (+25).
7.  **Game Over:** The game ends when the ball falls into a pothole. Your final score and a personalized message will be displayed.
8.  **Replay:** Click the "Replay" button on the Game Over screen to try again!

---

## Features

*   **Endless Runner:** The platform moves continuously, providing an endless challenge.
*   **Simple Controls:** Easy to learn with just `SPACE` for jumping and `P` for pausing.
*   **Dynamic Obstacles:** Potholes of varying sizes appear randomly.
*   **Collectibles:** Coins appear above some potholes, offering bonus points for skilled jumps.
*   **Scoring System:** Tracks score based on survival time, potholes jumped, and coins collected.
*   **Gradual Difficulty:** The platform speed increases over time, making the game progressively harder.
*   **Nickname Input:** Enter your nickname for a personalized Game Over message.
*   **Game States:** Clear Start, Playing, Paused, and Game Over screens.
*   **Visual Polish:** Includes particle effects for jumping/landing/collecting, simple parallaxing clouds, and a screen shake effect on game over.
*   **DOM Integration:** Uses P5.js DOM elements for the nickname input and start button.

---

## How to Run Locally

Since this is a P5.js project that relies on `index.html` to load the library and `sketch.js`, you need to run it through a local web server. Simply opening the `index.html` file directly in your browser might block some features due to browser security policies (CORS).

1.  **Clone or Download:** Get the project files onto your computer.
    ```bash
    git clone https://github.com/YourUsername/pothole-jumper.git
    cd pothole-jumper
    ```
    (Replace `YourUsername` with your actual GitHub username)
2.  **Use a Local Server:**
    *   **Using VS Code:** Install the "Live Server" extension, right-click on `index.html` in the file explorer, and choose "Open with Live Server".
    *   **Using Python:** If you have Python installed, navigate to the project directory in your terminal and run:
        *   Python 3: `python -m http.server`
        *   Python 2: `python -m SimpleHTTPServer`
        Then open your browser to `http://localhost:8000` (or the port indicated).
    *   **Using Node.js:** If you have Node.js installed, you can install a simple server globally:
        ```bash
        npm install -g http-server
        ```
        Then navigate to the project directory in your terminal and run:
        ```bash
        http-server -c-1
        ```
        Then open your browser to `http://localhost:8080` (or the port indicated).

---

## Future Enhancements Ideas

*   Sound Effects (Jump, Coin Collect, Game Over) & Background Music
*   Power-ups (e.g., temporary invincibility, score multiplier, slow-motion)
*   More Obstacle Types (e.g., moving potholes, barriers to slide under)
*   High Score Tracking (using Local Storage)
*   Visual Themes / Different Backgrounds
*   Mobile Controls (Touch input for jumping/pausing)

---

## Built With

*   [P5.js](https://p5js.org/) - A JavaScript library for creative coding.

---

## Author

Created with ❤️ by **Sumit Yadav**

---

## License

(Optional) You can add a license if you wish. The MIT license is a common and permissive choice for open-source projects.

Example:
> This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

