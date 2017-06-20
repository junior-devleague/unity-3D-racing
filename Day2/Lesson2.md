### Day 2 Lesson Plan

For today's lesson we will be focusing on creating our initial game environment, writing scripts for our player movement, and setting up our game camera.

### Getting Started

Download the Unity package attached to this repo. Open up unity and create a new project. Inside the editor, navigate to **Assests => import package => import custom package**. Find the unity package in your **downloads** folder and click ok. This will import the neccessary files you will need to start your project.

### Steps
1. Building the Track.
  - Create a new 3D **Quad** object.
  - Give this quad the name **"Track"**.
  - Reset the x,y,z positions back to zero.
  - Rotate the track so that is laying flat in your world. **Hint** rotate on the X-axis.
  - Create a new folder named **"Color Materials"**, create a new material for the track and apply it to track.
  - Change the **Scale** values of the track to **x=1000, y=150, z=1**.
  - Add track lines to your track by selecting from your **project window** under **Sample Scenes => prefabs => ground runway => runway lines.**. Open that up so you can see all the child objects. Click and drag just **ground runway lines** out of the parent object. Now you will conform the runway lines to your quad.

2. Building Walls Around Your Track
  - Create a new 3D object **Plane** with name **wall**
  - Rotate the plane on x-axis by **90 degrees**. Position walls around the edge of your quad so that your track is enclosed.
  - Create materials for your walls and apply them.
   **Wall Sizes**  right/left = scaleX = 100  front/back = scaleX = 15
   
3. Create your player object.
  - Navigate to **Standard Assests** and find the folder named **Vehicles**. Open that folder and click on **prefabs**. Click and drag the **car** prefab into your **Heirarchy** window.
  - Reset the X,Y,Z position to 0.
  - Rename the **car** object to **Player**. Assign it the tag **Player** in inspector window.
  - Create a new material and apply it to your Player object.
  
4. **STOP HERE LIVE CODING PLAYER CONTROLS**
    - Refer to CarController and CarUserControl scripts and follow along with your instructor.
    - Instructors refer to the repo wiki pages for complete code.
    
5. Add a camera to follow your player object
    - In your **project** window, find a folder named **cameras**. Navigate to **prefabs** and click and drag **multiPurposeCameraRig** into your heirarchy window.
    - In the **inspector** window, navigate where you see the **auto cam** script enables. Under that tab you will find some options that we need to change. First, under **target**, click on the small circle to the right. A window will pop up, from there you want to find and select **player**. This will tell the camera who to follow.
    - Second, change **move speed** to 10. This will allow the camera to keep up with the player object when its moving.
    - Third, change **turn speed** to 3. This will help the camera adjust when the player object turns sharply.
    - In your **hierarchy** window, click on **main camera** and in the **inspector** window next to the cameras name. Uncheck the box, this will disable the built in camera and tell Unity to use our camera.

![](http://i.imgur.com/keSjrkp.png)

6. **Stop Here, Time to Play**
    - Click the **play** button to see your world thus far. To control your player object, use the keys **WASD** on your keyboard.
    
