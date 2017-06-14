### Day 2 Lesson Plan

For today's lesson we will be focusing on creating our initial game environment, and writing scripts for our player movement.

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

2. Building Walls Around Your Track
  - Create a new 3D object **Plane** with name **wall**
  - Rotate the plane on x-axis by **90 degrees**. Position walls around the edge of your quad so that your track is enclosed.
  - Create materials for your walls and apply them.
   **Wall Sizes**  right/left = scaleX = 100  front/back = scaleX = 15
   
3. Create your player object.
  - Navigate to **Standard Assests** and find the folder named **Vehicles**. Open that folder and click on **prefabs**. Click and drag the **car** prefab into your **Heirarchy** window.
  - Reset the X,Y,Z position to 0.
