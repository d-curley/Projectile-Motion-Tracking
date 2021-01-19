# Projectile Motion Tracking
Credit to https://www.pyimagesearch.com/ for getting me started with the ball tracking portion! I added functionality that tracks movement and will estimate a quadratic equation to describe the projectile motion of a thrown object.

I would recommend using HSV Range Detection (https://docs.opencv.org/3.4/da/d97/tutorial_threshold_inRange.html) to set your HSV values at the top of the file. You can see I have a variety of color and lighting combinations already, but they will benefit from tweaking.

No arguments needed in the command prompt, just navigate to the file path and "python proj_motion.py" will get you up and running.

You will see the yellow circle and red dot tracking your object, but it will wait until you press "w" on the keyboard to start collecting points for projectile motion. 
Then press "e" to clear. "q" will exit the entire program. Note: Once you press "w" points will begin to be tracked, so it's best to have your object out of frame at the start.

Description: This python script uses image processing techniques to make a pink ball easier to track and log its x and y position in each frame.
Keeping track of these points, I am able to graph the projectile motion as the ball moves, and produce a line of best fit at the end of its trajectory.

Objective: As an engineering educator, I am always looking for authentic ways to incorporate math into hands-on activities, especially to support student design iteration. Projectile motion is a great mathematical exploration, but it can be hard to visualize the path of motion, let alone the equation associated with it. 
This system is the foundation of  educational tool to be integrated into engineering challenges, such as building a catapult or a ramp. 
