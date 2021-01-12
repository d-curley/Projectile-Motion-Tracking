# Projectile Motion Tracking
Credit to https://www.pyimagesearch.com/ for getting me started with the ball tracking portion! I added functionality that tracks movement and will estimate a quadratic equation to describe the projectile motion of a thrown object.

I would recommend using HSV Range Detection (https://docs.opencv.org/3.4/da/d97/tutorial_threshold_inRange.html) to set your HSV values at the top of the file. You can see I have a variety of color and lighting combinations already, but they will benefit from tweaking.

No arguments needed in the command prompt, just navigate to the file path and "python proj_motion.py" will get you up and running.

You will see the yellow circle and red dot tracking your object, but it will wait until you press "w" on the keyboard to start collecting points for projectile motion. Then press "e" to clear. "q" will exit the entire program. Note: Once you press "w" points will begin to be tracked, so it's best to have your object out of frame at the start.
