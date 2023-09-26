# ballmoving
This HTML document creates an interactive webpage called "RANDOM BALLS" that generates and animates random colored balls within a container. Here's a brief description of the key components:

: This declaration specifies the document type and version of HTML used. : The opening tag for the HTML document with the specified language attribute set to English.
: This
element with the id "container" serves as a visual area where random balls will be generated and animated. It is styled with a width of 1000px, a black border, a height of 600px, and a white background color. <script>: Inside the , there's a <script> block that contains JavaScript code responsible for creating and animating the random balls.
palet: An array containing different colors that can be randomly assigned to the balls.

balls, x_pos, y_pos, x_vel, and y_vel: Arrays to store information about each generated ball, including the ball element itself, its position (x and y coordinates), and its velocity (x and y components).

gravity: Sets the gravity effect on the balls' movement.

ballCount(n): A function that generates a specified number (n) of random balls moveBall(): A function responsible for animating the balls' movement. It updates the position of each ball based on its velocity, handles ball collisions with container boundaries, and updates the ball's style accordingly.

ballCount(10): This line initiates the creation of 10 random balls when the page loads. The animation continues indefinitely, with balls bouncing off the container boundaries due to the defined gravity effect. The balls' positions are updated at regular intervals using setTimeout, creating the appearance of animation.
