# DESCRIPTION
A Garry's Mod ACF turret written in Wiremod's expression 2.

This project requires two addon to work in-game:
* [Wiremod](https://steamcommunity.com/sharedfiles/filedetails/?id=160250458)
* [ACF](https://steamcommunity.com/sharedfiles/filedetails/?id=3248769144)

* ## INSTALLATION
Download the Project and install into:
C:\Program Files (x86)\Steam\steamapps\common\GarrysMod\garrysmod\

## FEATURES
* Simulates real-world tank turrets work by fixing its aim to a target vector when not moving the mouse
* Uses RT cam + RT screen to simulate a first person perspective instead of traditional "war thunder" style third person aiming
* Holo parenting for less physics jank
* Quaternians for angle calculations to prevent gimbal lock
* Basic PID controller for smoother aiming
* Built in control scheme and sound effects
* Grabs the players mouse delta directly for lag free calculations
* Outputs vector & ranger data for use in other E2s

## IMAGES
![fps](https://images.steamusercontent.com/ugc/16438235017581897184/D9BA9104AD2B6B392C167583F2ED70F2C846BD4D/)
![tps](https://images.steamusercontent.com/ugc/9547509457273291212/72C7EA41DA0908039F0B590A0521719D35E7920B/)
