# Homework2-CSC443
Maze Homework

Instructions : Due Date: Friday, December 12, 2025

Divide into teams of 5 and create an interactive 3D art gallery game using plain Three.js where players find and collect three pictures from the Brooklyn Museum art collection at archive.org. Each picture should be shown on a wall in one of five rooms, as if it were part of an art exhibit, along with other pictures. There should be about 10-15 pictures total (all from the same collection) in the gallery. The three pictures that must be found should be shown or described at the very start of the game. Each time the game is played, the three pictures that must be found are placed in random rooms.

Each room should feature unique vintage wallpaper textures and custom lighting. Implement first-person navigation using WASD and arrow keys and mouse for perspective (do not use OrbitControls). The player must click "paintings" to collect them.

A 3-minute timer (more or less) gradually darkens the gallery. The time limit should make the game a bit challenging, but not too difficult. Eventually, the gallery becomes completely dark, and the game is over if the three pictures have not been collected. The UI displays remaining time and collection progress (1/3, 2/3, 3/3) at the top of the screen. Include collision detection for walls and doorways. Some rooms should be connected by hallways. Naturally, each room should have a floor and ceiling as well—these do not have to be textured, but choose a color scheme that is fitting for an art gallery.

Victory: Collect all paintings before complete darkness; display each painting along with the painting's title and a direct archive.org link.

Defeat: Game over when darkness hits; offer restart option.

Build an immersive, polished experience showcasing Three.js fundamentals—scene composition, lighting, texture mapping, and user interaction—while maintaining engaging gameplay and clean architecture.

All code should be included in a single HTML file named index.html and published at https://prd-stuweb02.southernct.edu/~[username], where [username] is the user name of one of the students in your team. Use Three.js and (optionally) jQuery, but no other libraries or modules should be used. Each student (i.e., all team members) should send me a link to the game via email. In addition, in the body of the email each student should list the names of their teammates and briefly describe the work of each teammate. Then, describe your own work in more detail, being sure to include a bug report with solutions and a list of resources. This report should include at least some of the AI prompts you have used, and the name(s) of the AI used (DeepSeek, etc.). You are encouraged to use AI as an assistant. If you did not use AI at all, briefly describe why. Send the e-mail to pasqualonia1@southernct.edu. The subject of the e-mail should be: CSC 235 Homework 2: Art Gallery Game.
