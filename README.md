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
[Conversion Link](https://github.com/DaGoldenCat/Roblox/blob/8353c3c68a041b8b5980c0983c6382f6c94bf0bc/Source%20code/Player%20stats)
## Store & Buying items
### The local script sends data through a remote fuction, and the server checks if the player has enough and subtracts the total and clones the item to their inventory
## Menu & teleport to place
### Clones a GUI to the player and destroys the current gui in the middle of a transition
## Teams, Timer and Win condition
![Running App](https://github.com/DaGoldenCat/Roblox/blob/1fb712df0cb9c5c549e357553ace979971cf3dce/Pictures/Teams%20%26%20Timer.png?raw=true)
### Changes a player's team if requested, checks if at least 2 teams are valid, and updates the timer if correct. At the end of the timer or after 2 teams are empty, it checks the team base and awards if conditions are met
## Ragdoll
![Running App](https://github.com/DaGoldenCat/Roblox/blob/b0b10b67397df6d01c5c69ed74084570a48b5dbd/Pictures/Ragdoll.png?raw=true)
### Makes a for loop to changes the character's Motor6D's for BallSockets to create a ragdoll
## Crosshair, Bullet spread, and Recoil
![Running App](https://github.com/DaGoldenCat/Roblox/blob/74c02957c7e4735221dfa3c4a5d6b0e12405fd27/Pictures/Shotgun%20Spread.png?raw=true)
### Crosshair - Every frame the code keeps track of how fast the player moves, and makes a tween for how fast the player moves and what type the gun is
### Bullet Spread - The code takes a random point in the circle of the crosshair and raytraces it to where it hit in the world and sends the point to the server for another raytrace from the gun to the point
### Recoil - Makes a tween for the ammount of radians from the type of gun from a module script and changes the player's camera
