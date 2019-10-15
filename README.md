# Robo Rover

This project is modeled after the [NASA sample return challenge](https://www.nasa.gov/directorates/spacetech/centennial_challenges/sample_return_robot/index.html) and it will give you first hand experience with the three essential elements of robotics, which are perception, decision making and actuation.  You will carry out this project in a simulator environment built with the Unity game engine.

## The Simulator
The first step is to download the simulator build that's appropriate for your operating system.  Here are the links for [Linux](https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Linux_Roversim.zip), [Mac](	https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Mac_Roversim.zip), or [Windows](https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Windows_Roversim.zip).

## Telemetry and Record Data
In this project your analysis will be focused on image data coming from a camera mounted on the front of the rover. However, you will also have access to other data including the rover's position, throttle, brake, steering angle and speed, as well as roll, pitch and yaw angles.

Collectively, we'll refer to all this data as telemetry. If you're interacting with a real robot, you might be receiving telemetry data via WiFi or some other method. You can think of the telemetry data coming from the rover in this project as really just a bunch of sensor readings that are analogous to data you might get from a real rover using real sensors. In addition to the camera images showing the front view from the rover, a GPS might give you position, an inertial measurement unit (IMU) might give you roll, pitch and yaw etc.

You can record the image stream coming from this camera by hitting the "r" key (you'll need to hit "r" a second time to stop recording and save the data). You'll see a dialog box that allows you to choose a folder for saving data. Navigate to a folder where you would like to save the data and click "Select". The simulator will create a subfolder called "IMG" to store the image data and write a ".csv" file listing full image path names, and values for steering, throttle, brake, speed, position, pitch, yaw and roll.

## Launch Autonomous mode 
Launch the simulator, select autonomous mode. To get started with autonomous driving in the simulator, go ahead and run drive_rover.py by calling it at the terminal prompt 
## $ python drive_rover.py
