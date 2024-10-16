# Galaxy Generator with Three.js
This project creates a dynamic and customizable 3D galaxy using Three.js. Users can modify parameters such as galaxy size, number of branches, randomness, colors, and even enable or adjust the galaxy's spin, all via an interactive GUI.

Features
Dynamic galaxy generation with adjustable parameters.
Real-time updates when parameters are modified through a GUI interface.
Smooth camera controls using OrbitControls.
Spin animation that can be enabled or disabled, with customizable speed.
Installation

Run the project in a local development environment using any HTTP server (e.g., http-server, live-server).

Open the project in a web browser. The GUI will allow you to modify the galaxy’s appearance and behavior in real-time.

Controls
Count: Adjust the number of stars in the galaxy.
Size: Control the size of each star.
Radius: Change the overall radius of the galaxy.
Branches: Modify the number of branches in the spiral galaxy.
Spin: Adjust the amount of spin applied to the stars.
Randomness: Increase or decrease the randomness in star positioning.
Randomness Power: Fine-tune how randomness affects the star spread.
Inside Color: Change the color at the center of the galaxy.
Outside Color: Change the color at the outer edges of the galaxy.
Enable Spin: Toggle the spin animation on or off.
Spin Speed: Adjust the speed at which the galaxy rotates when spin is enabled.
Dependencies
Three.js
Lil-GUI
License
This project is licensed under the MIT License.

## Setup
Download [Node.js](https://nodejs.org/en/download/).
Run this followed commands:

``` bash
# Install dependencies (only the first time)
npm install

# Run the local server at localhost:8080
npm run dev

# Build for production in the dist/ directory
npm run build
```
