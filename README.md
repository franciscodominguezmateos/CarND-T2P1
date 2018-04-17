# Extended Kalman Filter Project Starter Code
Self-Driving Car Engineer Nanodegree Program

# project rubric accomplished

# Compiling

##  Your code should compile.
Yes it compile fine.
	
# Accuracy

## px, py, vx, vy output coordinates must have an RMSE <= [.11, .11, 0.52, 0.52] when using the file: "obj_pose-laser-radar-synthetic-input.txt" which is the same data file the simulator uses for Dataset 1. 
My RMSE are [0.09,0.11,0.44,0.41] I had to change noise_ax and noise_ay to 15 from 9.

# Follows the Correct Algorithm

## Your Sensor Fusion algorithm follows the general processing flow as taught in the preceding lessons.
Yes, I have filled the template code.	

## Your Kalman Filter algorithm handles the first measurements appropriately.
Yes, if it get a LASER measurement it init state from px and py, if it get a RADAR measurement it changes from polar to cartesian. 

## Your Kalman Filter algorithm first predicts then updates.
Yes in the template code for ProcessMeasurement() it first predicts and then updates.

## Your Kalman Filter can handle radar and lidar measurements.
Sure in radar measurement I use the jacobian
	

# Code Efficiency

## Your algorithm should avoid unnecessary calculations.
I try to give the most importance to clarity, and less to speed, but I try to use reference where I can in order to speed the code.
