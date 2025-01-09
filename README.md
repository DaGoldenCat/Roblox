# DaGoldenCat's Portfolio
## Personal Info
### Email - dagoldencat3@gmail.com
### Roblox Account - DaGoldenCat
### Discord - jeffory3
## Certifications
### Computer Programming I exam from youscience, 92.89%
### 1.5 years of coding (with classes)
### Luau, Python, Java, C++, JS & HTML
# Work
## I alone have written all of the programs below, no code has been directly copied from another person
## Player Stats & Gamepasses
![Running App](https://github.com/DaGoldenCat/Roblox/blob/2df32bb13fc6b4884561f5b54f73f3cf9ebbaa1c/Pictures/Player%20Stats.png?raw=true)
### Every once in a while the server sends every player a list of each top player with pcalls, their score is sent in order through events
### If a player owns a gamepass, their score is earned in 1/3 of the time
## Store & Buying items
### The local script sends data through a remote fuction, and the server checks if the player has enough and subtracts the total and clones the item to their inventory
## Crosshair, Bullet spread, and Recoil
![Running App](https://github.com/DaGoldenCat/Roblox/blob/74c02957c7e4735221dfa3c4a5d6b0e12405fd27/Pictures/Shotgun%20Spread.png?raw=true)
### Crosshair - Every frame the code keeps track of how fast the player moves, and makes a tween for how fast the player moves and what type the gun is.
### Bullet Spread - The code takes a random point in the circle of the crosshair and raytraces it to where it hit in the world and sends the point to the server for another raytrace from the gun to the point.
### Recoil - Makes a tween for the radians from the type of gun and changes the player's camera
