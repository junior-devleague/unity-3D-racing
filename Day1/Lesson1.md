# Day 1 Lesson Plan

Today we will be introducing you to Unity and the editor window. By end of day you should be comfortable with using the basic features of the editor. **Instructors**- remind students to bring a USB drive to save their work.

### Intro to the Unity UI
  1.  **Create a new Unity project**. Navigate to **file -> New Project**. Give your project a name. Upon clicking **"create project"** the game editor window will appear.
  ![](https://github.com/junior-devleague/spring-break-unity/blob/master/Day1/Screenshots/editor.png)
  2. **Understanding the different windows on the editor.**
    - **Top Left** = This is your **Scene**. This is where you can see your objects in your 3D world and can adjust them using the tools above
    - **Bottom Left** = This window is your actual **Game** window. This will show you how your game will look and feel at its current state when rendered.
    - **Middle Top** = This is your **Hierarchy** window. It is where you will store all of the actual game objects such as objects.
    - **Middle Bottom** = This window is your **Project** window. It holds your file structure for your game and contains all built-in assests, loaded assests, and files you create.
    - **Top right** = This window is the **Inspector** window. This is where you can modify your game objects.
   3. **Using navigational tools.** This moves componets around the 3D world. Create a 3D object- Sphere **GameObject=>3D Object=>Sphere** and use the tools to move it around in the world.
   
   ![](http://i.imgur.com/WJa2Sdk.png)
   
   4. **Using Inspector window**  to modify your sphere such as position, rotation, scale, lighting, and materials. Take a few minutes to explore the Inspector window. Look at the different components that make up a 3D sphere!!
   
   ![](http://i.imgur.com/a84WD03.png)
   
   5. **Understanding the Project window.** This is where you will make folders to store everything you will use for your game. It is important to keep good file structure as your game will become very complex fast.
    - In the Project window click **create=>folder** and name it **materials**. We will cover what materials are later. This is an example of keeping your game files organized to find things easier.

  ![](http://i.imgur.com/E4vQMlt.png)
  
  6. **Rendering your game.** Click the **play** button on the middle top of the editor. This will render your game at its current state so you can see how your game is working/looks thus far.
  
  ## Lets get some practice with the editor
  
  **Steps**
  1. Create a 3D Quad object. **GameObject=>3D Object=>Quad**.
  2. Using the **Inspector Window** or **Navigational Tools**, rotate your quad so that it is laying flat in your world.
  3. Adjust the **length & width** of your quad so we have a bit of room to work with.
  4. Inside your **materials** folder, create a new **material** and name it **QuadColor**. 
    - In your inspector window, click the dropper to select a color for your material. The color chosen should now show up next to the dropper.
    - Drag and drop your **QuadColor** onto the quad. Your quad should now have the color you have chosen. Your screen should now look something like this.
    
![](http://i.imgur.com/zSDnK9I.png)

  5. Add a 3D sphere to your game, create a new **material** and name it **SphereColor**. Apply the color to the sphere.
  ![](http://i.imgur.com/JqGuox9.png)
  6. With your **Sphere** selected, navigate to the bottom of **Inspector** and click on **Add Component**
    - In the search field, type **RigidBody** and select it. This will add the component to your object.
    - In the **Inspector** window, uncheck **Sphere Collider** then press the **play** button and see what happens??
    
 7. Add movement to your sphere.
    - In the **Inspector** window click on **Add Component** and search for **Rigid Body** and click to add this component to your sphere.
    - Create a new C# script and name it **Move**
    - **Live Code Move Script** - Instructor refer to wiki page **SphereMove**
    - Drag and drop **Move** script onto the sphere object.
    - In the inspector window under the Move script component, change **speed** to 10;
    - Save game, and click play. To move the sphere use keys **wasd**. Note, make sure gravity is turned on the sphere.
    
