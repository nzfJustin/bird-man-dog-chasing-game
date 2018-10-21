
The game instruction is in “Complexity and impressive underlying mechanics” part. Have fun catching the bird and avoiding the dog!
---------------------------------------------------------------------------------------------------------------------------
• [4 points] Make use of hierarchical objects with at least three levels (e.g., a human arm)

   * The hierarchical object that I create is the bird. It has 3 hierarchy levels: head - body - wing, the code is on ‘draw_bird’ function.  
---------------------------------------------------------------------------------------------------------------------------• [4 points] Demonstrate the camera tracking a moving object sometime, by overwriting the camera matrix using ​lookAt()​.

   * I use camera to track the movement of the person using lookAt at ‘display’ part. First of all I use trigonometric functions to move the position of the camera to let the player have a overall look of the scene, Then I achieve a montage by making the position of the camera at a fixed point and let it track the movement of person. also, If the person catch the bird, then the camera position will be changed to the position of the bird looking downwards. 
---------------------------------------------------------------------------------------------------------------------------• [6 points] Design polygonal objects of your own to supplement the existing ones. To specify these shapes you must providenovel positions, normals, and texture coordinates to the graphics card by extending class Shape().

  * The polygon hat I design is the wing and tail of the bird. The corresponding code is ‘wing’ and ’tail’ in the Shape() file. 
---------------------------------------------------------------------------------------------------------------------------• [2 points] Assign reasonable texture coordinates to, and texture, an instance of your custom polygonal object. Either texture it by mapping an image file, or procedurally (more like the Funny_Shader demo).

   * I create a texture called wingcolor and apply it to the bird wing,I also create lecture called forest and grass and apply it to the background,  they are in this.define_data_members
---------------------------------------------------------------------------------------------------------------------------• [2 points] Your texture coordinates from the previous step must be designed to create an abrupt transition (discontinuity) along some edge(s) of the shape. Flat shading should be evident there when drawn and lit with the provided Phong reflection model.Explain in your README where to look for it.

   * The texture that I create is wingcolor, which consists of blue and green triangle. I apply it to the bird wing and achieve a beautiful abrupt transition of blue and green on the flat shading. 
---------------------------------------------------------------------------------------------------------------------------• [2 points] Real-time speed. Make sure that your animation runs at the same speed i.e., one simulated second correspondsroughly to one real second regardless of the machine your program runs on (even a ridiculously fast one from the future). The variable animation_time inside the graphics_state object is your gauge of the passage of real seconds.

   * I apply real time speed on the flying orbit of bird and the camera movement at the first of the game(to give a overall scene of the game).I apply this on ‘display’ part. 
---------------------------------------------------------------------------------------------------------------------------• [2 points] Display the frame rate of your program on the graphics window, taking advantage of the update_strings() method that each Scene_Component object runs each frame.

   * I use a function called update_strings() with variable second, temp_time and temp_f to show frame rate. The display is called fsp in the scene. 
---------------------------------------------------------------------------------------------------------------------------• [4 points] Creativity (story, aesthetic style, etc).

   * The game is two-players game which happens in a forest. A person comes in the forest and see a beautiful birds flying around a tree and a dog notices the appearance of the person. The person wants to catch the bird and the dog wants to catch the person. 
---------------------------------------------------------------------------------------------------------------------------
• [4 points] Complexity and impressive underlying mechanics.

   * The person could move in 6 direction controlled by 6 keyboard: “j” for up, “l” for down, “left” for left,”right” for right, ”down” for forward and ”up” for backward. The dog can move in 4 directions controlled by 4 keyboards” “5” for forward ”6” for backward ”7” for left and ”8” for right. There is also a Health Point of the person initially 100. If the person catch the bird once, his Health Point will increase by 1 and if the person is caught by the dog, his Health Point will decrease by 1. If the Health Point decrease to 0, then the game will become red indicating that the person is dead!
---------------------------------------------------------------------------------------------------------------------------

• [5 points] Overall quality: Fluidity of object and camera motion, ​attention to detail​ in scene construction, etc.• [For participation in the in-class screening and contest] Make and submit a movie of your animation (length 90 sec or less) usingyour favorite screen recording application (e.g., camstudio/quicktime). If your program is interactive, submit a video of it being used. Make sure you encode your movie to be below the CCLE limit of 100MB, and observe the 90s limit.