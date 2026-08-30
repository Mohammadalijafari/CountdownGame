⏱️ The Almost Final Countdown

A small React reflex game: pick a difficulty, start the timer, and try to hit Stop as close to zero as possible — without going over. Stop too early or too late and you lose; the closer you cut it, the higher your score.

Built while practicing React's useRef, useImperativeHandle, and createPortal APIs.

🎮 How to Play
(Optional) Enter your name at the top of the page.
Choose a challenge — Easy, Not easy, Getting tough, or Pros only.
Click Start Challenge to begin the countdown.
Click Stop Challenge right before the timer hits zero.
If you stop in time, your score (0–100) is based on how close you got to the target time. If the timer runs out first, you lose the round.
Close the result dialog and try again — beat your own score!
🧩 Difficulty Levels
Challenge	Target Time
Easy	1 second
Not easy	5 seconds
Getting tough	10 seconds
Pros only	15 seconds
🛠️ Tech Stack
React 19
Vite — dev server & build tool
ESLint for linting
📂 Project Structure
CountdownGame/
├── public/
│   └── vite.svg
├── src/
│   ├── components/
│   │   ├── Player.jsx           # Player name input
│   │   ├── TimerChallenge.jsx   # Countdown logic per difficulty
│   │   └── ResultModal.jsx      # Win/lose dialog (uses createPortal)
│   ├── App.jsx                  # Renders Player + all challenges
│   ├── main.jsx                 # App entry point
│   └── index.css
├── index.html
├── package.json
└── vite.config.js
🚀 Getting Started
Prerequisites
Node.js (v18 or later recommended)
npm (comes with Node.js)
Installation & Running Locally
bash
# Clone the repository
git clone https://github.com/Mohammadalijafari/CountdownGame.git
cd CountdownGame

# Install dependencies
npm install

# Start the dev server
npm run dev

Then open the URL shown in your terminal (usually http://localhost:5173).

Other Scripts
Command	Description
npm run dev	Start the Vite development server
npm run build	Build an optimized production bundle
npm run preview	Preview the production build locally
npm run lint	Run ESLint over the project
🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to fork the repo and open a pull request.

👤 Author

Mohammadali Jafari GitHub: @Mohammadalijafari
