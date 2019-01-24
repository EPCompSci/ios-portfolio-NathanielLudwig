# iOS-Portfolio
2018-2019 Portfolio

About me project - My app
In this project I learned how to create buttons and create layouts in the storyboard editor. At the time this was a big accomplishment.

First Project - guess 100:
For my first ios project I decided to learn swift by recreating a simple game I made last year in java. I learned how to create a app layout and UI in xCode and connect the screen elements to the code. Being able to connect visual elements to code was a feature that was new to me and was not in java. The app allows the user to guess a number from 0 to 100 using a picker wheel. The game also tracks score and removes numbers that have been eliminated. 

My Second Game:
My second game I decided to focus on learning spritekit. It is not a finished project but just a test. I learned how to create sprites and add physics. I learned about all the physics settings in spritekit which helped me create future games. I also learned features specific to apple devices like 3d touch and touch feedback. In the app you can fling around emojis with your finger and see how the physics interact. There is also a spinner that spins when you press it with a hard touch.

NewGame:
This was another project that I used to learn how sprite kit works. My goal was to create a game using tiles because tile textures can make a nice looking and functioning game with less artistic skill. I figured out how to create a tile map and how to use the automapper to place random tiles from a tile group.

Dungeongame / Battledudes:
Dungeongame is a role playing game that was supposed to be my final project before it turned into Battledudes. The app features a level that the character can walk around in using directional buttons. The dude also has walking animations based on where he is pointing and collides with walls. My main take aways were being able to assign physics bodies to tiles by making invisible SKNodes on tiles and using SKactions to animate the dude while he is walking.

Gravity Dude / coolgame:
Gravity Dude is a physics based game where you have to move your character through the level only by rotating its arms and legs. It requires players to dodge objects. You are able to reverse the gravity and go in slow motion mode. The game also auto saves your progress if you leave the app and come back. The first challenge I faced getting the sprites arms and legs connected to its torso. I learned how to use SKJoints to solve this. Next I had to be able to rotate the arms and legs to point to the touch position. This issue got complicated quick with points being in different coordinate systems. The game also faced performance issues with the ammount of nodes on the screen at once. I was able to fix this by making the walls 3 blocks thick of nodes instead of all the walls having nodes. 
