# 2d-collision-manager
A simple and fast 2d collision managing system, designed to be utilized for io games.
Note that this system does not support collision management for all polygon types--only circles and axis-aligned squares (for simple hitbox detection).
At the top of the collision system's code, constants for configuration (i.e. room data, physics config like gravity, friction, and collision accelerations) can be found.
The demo server and client already provides a basic demo of the system in action, while the collision_manager.rs file provides the raw, non-networked code for the collision manager only. 

Some examples from the demo system:
10k entities in a 1024x1024 space, with a giant immovable wall in the middle:
![collision demo](https://github.com/user-attachments/assets/56394174-3f88-455f-ba57-0d3d2f20125b)
A video with 1k entities (for easier viewing of the physics) in the same 1024x1024 space, with the same immovable wall:
[collision demo video](https://github.com/user-attachments/assets/c5aac9a9-3a0b-4179-9632-15f5436b3144)

