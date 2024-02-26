# game-fall-down

What is Fall Down?
Fall down is a simple game which has the only objective of preventing the ball from going 
off the top of the screen. It is a strategic, single player game which can be played by 
anyone without any age restrictions. There is no need of any pre-required knowledge to 
play this game. The game starts with a ball standing on a brick and there will be more
brick stairs below, the user has to use the keys to control the movement of the ball left and 
right. The ball should fall and land on maximum number of brick stairs in order to get 
maximum score. The only aim of the game is, the ball should not hit the top of the screen.

How the Fall Dow Game works?
➢ The user should control the ball movements.
➢ The higher the brick stairs you land, more points you score.
➢ The ball should not hit the top of the screen.
➢ The game ends when you hit the top of the screen.
➢ The final score is calculated based on the total number of stairs you landed.
How to play the game?
➢ The player can start the game by moving the ball in any direction.
➢ They can control the ball’s movement by pressing the left and right arrow keys.
➢ The score is calculated by counting the total number of stairs landed by the ball.
➢ The ball should not hit the top of the screen.
➢ When the ball hits the top of the screen, the game ends.

Tools:
Technology Used:
• Java
Software Requirements:
• JWD
• Swing
• Eclipse
• AWT Package
Hardware Requirements:
• Hard Disk – 2GB.
• RAM – 512 MB.
• Processor-Dual Core or Above.

PROJECT MODULES

BALL MODULEThis Ball module is all about the basic characteristics of the ball in this game and also 
about getting new position of the ball every time it changes its position due to the 
movement in any direction either left or right. There are different methods created to move 
a ball in the direction we want to by pressing the direction arrows and also to get the 
current new position of the ball in the means of coordinates. For example, if we want to 
move the ball by left, the method move left will be called and executed. This will work by 
reducing some constant value of the x coordinate from the current position of the ball. 
Similarly for performing left movement, the method move left will be called which will 
work by increasing the constant value of x coordinate. The get position method will help 
us to get the present position of the ball, every time if the ball movement changes. Finally, 
we created the virtual ball by creating a circle shape and filling it with the colour black.

BRICK MODULEThis brick module is all about creating a shape and structure of the brick and placing it in a 
position as the game requires. The work is not done only on creating a shape and structure 
of the brick; we also have to create a virtual movement restriction created by the actual 
brick wall on the ball we created. It means, in terms of logic, if we want to make a ball to 
land on the brick, we can create this scenario virtually by ensuring that the ball should not 
keep falling down once the coordinates of the ball intersects the coordinate of the brick we 
created. This is how it works. The brick also has its position coordinates as like the ball 
and we also need to create some random length of brick for every particular constant 
interval along with the screen which is moving towards the top of the screen. We created a 
structure of the brick using rectangle shape and by painting it with a red color, so that it 
will look like a brick.

MOVEMENT MODULEThis module is responsible with the movements related in the game. Movement of the ball 
and the moving background is an integral part of this game hence we can subdivide this 
section into first ball movement and next moving background. So let’s discuss on this one 
by one.
Ball movement- Using the navigation keys, we can set the movements of the ball using the 
java awt package. This module specifies the direction and uniformity in its movement. The 
ball can be navigated to left and right directions accordingly as per the requirements of the 
game. Ball movement is also responsible for halting the game as the game gets terminated 
as soon as the ball touches the upper bound.
Moving background- This module specifies the movement of the background which helps 
in setting constraints on this game. As the layer of brick moves forward in upper direction, 
we score points and thus it also helps in scoring the points through this game.
