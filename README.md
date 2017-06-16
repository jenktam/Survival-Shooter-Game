# Survival Shooter Game

This is an isometric shooter game about a boy who has a nightmare about his toys that have joined forces to eat him.

# Making Player

## Animations
* Within project, build animations folder, create animator controller.
* Will show tree of player actions and can create scripts for what the player can do. This tree will display them all. Ex: Idle, Move, Death
* Can add links to show how state will change by right clicks on actions and then connecting them to other actions. 
* Make sure to right click on the arrows and uncheck 'Has Exit Time'. This removes any delays with animation transfers

# Camera Tips

## Orthographic view > perspective view
* allows 2D views of 3D objects, which seems more natural. 
* Represents exact shape of an object from one side at a time as you are looking perpendicularly to it. Depth not shown.

* Lerp: smoothly moves between 2 positions via Vector3.Lerp()
* Prefabs: hard-drive asset that can save, export and use in other apps, files. much more beneficial to turn things into prefabs

# Enemies

## Adding Enemies
* Hit Particles - assets that add affects when character hit


## Triggers
* Calls function script whenever something rouches trigger
* not interested in trigger's interactions with scene view
* on Sphere Collider, tick 'Is Trigger' to indicate that it won't bump into anything, but just a trigger
* Nav Mesh Agent Component
    * not moving enemies using physics like with player
    * special AI to move enemies
    * will naturally track and follow target while avoiding objects
    * bake nav mesh agents