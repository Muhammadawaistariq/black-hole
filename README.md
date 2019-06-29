# black-hole
android game made with unity 3D

COuntDown Timer.cs
//Update function use to update the timer in the scene and exit if timer complete its time limit
ballControlScript.cs
Start  		// initialize the objects 
Update		// Getting devices accelerometer data in X and Y direction
		// multiplied by move speed modifier
Myfunction
FixedUpdate // Setting a velocity to Rigidbody2D component according to accelerometer data
setIsDeadTrue // Method is invoked by DeathHoleScript when ball touches deathHole collider
setYouWinToTrue // Method is inviked by exit hole game object when ball thouches its collider
RestartScene // Method to restart current scene
ScoreCount.cs
//Count and update score 
DeathHoleScript.cs
//Trigger if object collide to death holes
ExitHoleScript.cs
//Trigger if object collide to Exit holes
MenuController.cs
//Control menu funtions 
Start
Level_01
Level_02
Level_03
Level_04
ExitOk
