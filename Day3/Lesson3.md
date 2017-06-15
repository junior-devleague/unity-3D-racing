### Day 3 Lesson Plan

Today we will be adding enemy players, enemy navigation, implementing a game menu, and writing scripts for a finish line.

### Steps

1. Adding a finish line to your track.
  - Create a new 3D game object **cube**
  - Move **cube** to one end of your track. Transform the cube so that its flat and spans the width of your finish line.
  
 ![](http://i.imgur.com/KyEA159.png)
 - In your **inpector** window under **Box Collider**, make sure that **is Trigger** is checked.
 - Edit your Collider perimeter **Instructor will show you this**.
 
2. Adding functionality to your finish line.
 - **Stop Here** 
 - Instructors live code **Finish line** script found in repo wiki. 
 - Test that script displays Debug Log when car passes through the finish line.
 
 3. Adding Enemy Cars
    - In your **Hierarchy** window, right-click on player and select **duplicate**. Rename this car **Enemy**.
    - Create a new material and apply to enemy player.
    
 4. Adding Navigation for Enemy Cars.
  - **Instructors will live code NavBake**
  - With your Enemy player selected, navigate to **inspector** window and click **add Component**. Search for **nav mesh agent** and click ok.
  - ** Instructors live-code Nav Script** - refer to wiki in repo for code.
