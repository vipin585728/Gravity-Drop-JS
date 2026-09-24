🌌 Gravity Drop JS

Gravity Drop JS is an interactive HTML5 Canvas physics experiment where emojis behave like physical objects affected by gravity, velocity, bouncing, and wall collisions.

Click or tap anywhere on the screen to drop a burst of random emojis and watch them bounce around the screen. 🎮✨

🚀 Features

- 🎯 Click anywhere to spawn emojis
- 📱 Touch support for mobile devices
- 🌍 Real-time gravity simulation
- 🏀 Bouncing floor physics
- 🧱 Wall collision detection
- 🎲 Random emoji selection
- 💨 Random horizontal and vertical velocity
- ⚡ Smooth animation using "requestAnimationFrame()"
- 📦 No external libraries or dependencies

🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- HTML5 Canvas API

🎮 How to Play

1. Open "index.html" in your browser.
2. Click anywhere on the screen.
3. Multiple emojis will appear at the clicked position.
4. Watch them fall under gravity and bounce off the bottom.
5. On mobile, touch and move your finger across the screen.

📂 Project Structure

Gravity-Drop-JS/
│
└── index.html

The project is intentionally built as a single HTML file, making it easy to understand, modify, and run.

🧠 Physics Behind the Project

Each emoji is represented as a particle with its own physical properties:

gravity = 0.3;
bounce = 0.7;

During every animation frame:

1. Gravity increases the vertical velocity.
2. The emoji position is updated using its velocity.
3. Floor collisions reverse the vertical velocity.
4. Wall collisions reverse the horizontal velocity.
5. The canvas is redrawn continuously.

This creates a simple but fun 2D physics simulation using JavaScript.

🎨 Emojis

The project randomly selects emojis from:

🔥 💻 ⚡ 🚀 ⭐ 💎 💡

You can easily add your own emojis to the array and create a completely different theme.

⚙️ Customization

Experiment with these values to change the physics:

- "gravity" → Controls how quickly emojis fall
- "bounce" → Controls how high emojis bounce
- "speedX" → Controls horizontal movement
- "speedY" → Controls initial upward velocity
- "size" → Controls emoji size
- Number of particles → Controls how many emojis spawn per click

📱 Responsive

The canvas automatically adjusts to the browser window size and works on:

- 🖥️ Desktop
- 📱 Mobile
- 💻 Laptop
- 📲 Touch devices

🌐 Live Demo

After enabling GitHub Pages, add your demo link here:

https://YOUR-USERNAME.github.io/gravity-drop-js/

📸 Preview

Add a screenshot or GIF of your project:

![Gravity Drop JS Preview](preview.png)

🤝 Contributing

Feel free to fork this project and experiment with the physics.

You can add features such as:

- 💨 Air resistance
- 🌀 Wind effects
- 🪐 Different gravity modes
- 🔊 Collision sounds
- 🎯 Score system
- 🧲 Magnetic attraction
- 🌈 Particle effects

Pull requests and creative improvements are welcome!

📄 License

This project is open-source and available under the MIT License.

---

⭐ If you enjoyed this project, consider giving it a star!

Made with ❤️ using HTML, CSS & JavaScript.
