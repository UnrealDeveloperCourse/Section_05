# Testing Grounds

Unreal Developer Course that implements a custom version of streamingLevels using a combination of C++ and Blueprints 

![Current Screen Shot](Saved/Screenshots/Windows/CurrentScreenShot.png)

[Gameplay footage](https://www.youtube.com/playlist?list=PLXbhb1vwcM98WjQ5YJ2dHq_fJN9ZSyxFa)


## Going Forward

Move on to create new game using streamingLevels and implement things learned in this project with animation and procedural prop placement.


## 2018-07-22 Converted project to UE 4.20 built from source

Useful if only to practice fixing issues converting a project to a new engine version. Checkout 40a580a on master and run in UE 4.18.3 to experience a smoother running project.

Issues with this project

- EQS pathfinding is busted
- New RecastNavMesh-Default object created by default
- Slight difference in engine code with VR controller for character fixed
- Navigation system moved to new module
- Environment query graph had to be manually enabled in DefaultEngine.ini

Things that survived

- A useful actor pooling class
- NavMeshes and NavigationSystem
- Character gameplay, animation, and procedural streaming tile level


## Character Rotation Architecture

![](Saved/Screenshots/Windows/character_rotation_architecture.png)


## Character Movement Architecture

![Character Movement Architecture](Saved/Screenshots/Windows/character_movement_architecture.png)


## Sphere Cast Collision Detection

![Sphere Cast Collision Detection](Saved/Screenshots/Windows/Spawn_Collision_Detection_DebugCapsule.png)


## EQS Pathfinding

![EQS Pathfinding](Saved/Screenshots/Windows/EQS_Debug.png)


## Actor Life Cycle

![Actor Life Cycle](Saved/Downloads/ActorLifeCycle1.jpg)
