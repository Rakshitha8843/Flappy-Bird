# Flappy Bird

Flappy Bird is an endless game that involves a bird that the player can control. It is the player's responsibility to keep the bird from running into obstacles like pipes. The bird gains one point for each time it goes through the pipes. The bird must crash into the pipes or fall to the ground in order for the game to conclude. 
The steps that must be done to develop this game are explained in the sections that follow.<br>

**1. HTML Section** : This is where the game's components are created and loaded. The background, bird, hurdles, and scoring elements have all been chosen. Next, we create the index.js and style.css files and link to them.<br>

**2. CSS Section** : This section allows to adjust the game item's size, position, and style based on ones needs.<br>

**3. Java Script Section** : The portion of the code that manages the moving objects and the game's state is contained in this section. In this part, the steps listed below must be completed.<br>
 a. Get a reference to bird and background image in JavaScript file.<br>
 b. Set some values for background scrolling speed, the flying speed of the bird, and gravity.<br>
 c. Create the infinite scrolling background.
 d. To switch the game state to the play state and apply gravity to the bird by lowering the gravity value from the bird's y-coordinate every frame, add an event listener and set it to listen for the keypress of "enter."<br>
 e. At the end of the view width, create hurdles (pipes) that are initially invisible. Then, when the background moves, reduce the pipe's x-coordinate by the background scrolling value to make the bird appear to be moving.<br>
 f. Apply collision with pipes and the ground. If the bird collides, the game will terminate and a message suggesting a reset will be displayed.<br>
 g. After each pipe navigation that is successful, the score value is increased.
    
