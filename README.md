# CARLA-ManualControl

Thanks to all the contributers of CARLA Simulator, I really love the work you guys are doing!

This is my modification of the manual_control.py for CARLA-Simulator. I really love the concept of CARLA-Simulator. 
In this implementation, I want to make the manual_control.py much more appeasing to gamers like me so that more 
people will be using it. CARLA-Simulator need not just be for development of autonomous vehicles, it can also be used as
a game engine (it is based UNREAL engine with Python API after all...) for us to make games from it... We could make it so
that gamers come and play around in the game while developers make AI cars to be trained in the environment through the 
multiplayer setup... 

I have eliminated the dead zone issue which causes steering drive... Also I made it such that user can choose if they want
GTA 5 kind of steering, where the steering input varies with the speed of the vehicle. This is to avoid understeering situations
when the car is moving too fast and the steering input is too much...

## Controller Mapping
![XBOX Control Mapping](https://github.com/YEOWEIHNGWHYELAB/CARLA-ManualControl/blob/main/Images/XboxKey.png)

## Formula for Steering Input 
![Steering INPUT Formula](https://github.com/YEOWEIHNGWHYELAB/CARLA-ManualControl/blob/main/Images/FormulaForSteeringInput.png)
