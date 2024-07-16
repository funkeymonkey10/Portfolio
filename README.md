# Portfolio
A portfolio showcasing multiple projects created in multiple programming languages. (C++, C#, JavaScript).
**Portfolio Website:** https://sites.google.com/view/nathansshowcase/home

**Custom 2D/3D Graphics Engine:**

**Programming Languages:** 
C++, OpenGL Shading Language (GLSL)

**API's:**
OpenGL - Graphics Backend
GLFW - Keyboard and mouse input 
GLM - Matrix  Calculation
stb_image - Image/texture loading
FreeType - Font processing
SoLoud - Sound backend
ReactPhysics3D - Collision and physics simulation

**Description:**
A custom engine that displays and manipulates objects in a virtual space. The engine also takes keyboard input,  processes fonts, detects object collision, and plays sound. The objects in the engine can be customized using custom models and images. Text in the engine is built using the font provided by the user and the texts size, color, and position is customizable.


**Unity 3D Mesh Manipulation, Shading, and Lighting:**

**Languages:** C#

**API:** Unity Engine

**Description:** Renders a 3D plane that can be manipulated at points and diffusely shaded based on point position. The user can also modify the position, size, and rotation of the planes texture. Lastly the resolution slider increases/decreases the amount of points on the given plane. Moving the slider after making adjustments resets the plane back to a flat horizontal position.  The menu in the top left hand corner allows the user to switch to a cylinder and make the same adjustments to the objects points.


**Game Engine Editor (Group Project):**

**Languages:** JavaScript, HTML

**API:** WebGL

**Description:** A 2D game engine that allows the user to make changes to game objects and then save those changes to be later loaded back into the engine. Only the position or size of the squares can be adjusted within the game space. After one is done editing the scene, the save button is pressed to save the file to a local hard drive. If the user wants to load a saved scene, a properly formatted JSON file must be selected locally before pressing the load button. Loading a scene will reset any objects currently on screen to the state of loaded scene.

The project uses WebGL for the graphics API and coded in JavaScript. Saved scenes are exported in JSON format and must keep the specified format when downloaded on to a local drive.
