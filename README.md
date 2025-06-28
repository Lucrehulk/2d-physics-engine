# 2d-collision-manager
A simple and fast 2d collision managing system, designed to be utilized for io games.
Note that this system does not support collision management for all polygon types--only circles and axis-aligned squares (for simple hitbox detection).
At the top of the collision system's code, constants for configuration (i.e. room data, physics config like gravity, friction, and collision accelerations) can be found.
The demo server and client already provides a basic demo of the system in action, while the collision_manager.rs file provides the raw, non-networked code for the collision manager only. 

Some examples from the demo system:
![Screenshot 2025-06-28 1406[video (6).webm](https://github.com/user-attachments/assets/9b3833d2-7d03-43a6-bb96-d4fe7dc9bbca)
01](https://github.com/user-attachments/assets/cd72ffbd-2627-49a8-af55-49f7dc096ec7)

