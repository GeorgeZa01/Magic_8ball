**Classic Magic 8-Ball Web App
This is a standalone, single-file web application that simulates the classic Magic 8-Ball toy experience. It features a responsive, dark-themed UI built with Tailwind CSS and relies entirely on Vanilla JavaScript for logic and CSS keyframes for the shake animation.

Key Features
Classic Functionality: Users input a question, and the application generates a random answer from the nine classic Magic 8-Ball phrases.

2D Design & Animation: The application features a sharp 2D visual design with a custom CSS shake animation that mimics the physical act of shaking the toy.

Pure Client-Side Logic: No external APIs or servers are required. All prediction logic is handled locally in JavaScript.

Fully Responsive: The layout adjusts seamlessly across mobile and desktop devices.

Tech Stack: HTML5, Vanilla JavaScript, and Tailwind CSS.

Getting Started
Since this is a single HTML file, getting started is simple:

Save the file: Save the code above as index.html.

Open in Browser: Double-click index.html to open the application in any modern web browser.

Prediction Logic
The application uses an explicit if/else if/else conditional chain (internally optimized via array lookup in the current code) combined with Math.floor(Math.random() * 9) to ensure the nine predictions are selected with equal probability:

Affirmative: 3

Non-committal/Hazy: 3

Negative: 3
