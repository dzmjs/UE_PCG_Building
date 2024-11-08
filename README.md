# UE_PCG_Building
This Unreal Engine project introduces a smart asset designed for dynamic building generation. Leveraging procedural content generation (PCG), the asset can adjust building width, length, and number of floors in real-time, making it versatile for various game environments. 
## Preview
![effect]("./20241108115038.png")

## Requirement
 - UE version > 5.3 (recommended version:5.4.4)
 - UE plugin: Procedural Content Generation Framework(PCG) is enable.

## How to install
 `git clone` This project, you will find a file folder named `Content`, copy this folder to your UE project.

## How to use
1. Drag `BP_Building` to your Level.
2. In details, change the parameters in Default. For example, Wall Size: 310, Wall Tickness: 40, Unique Floor Offset: 2.
3. Click anchor point in Spline, then move the position. The building shape is changed.

## Reference material 
fab resource: Modular_Building_Window, Patterned_Floor_Tiles, Roof_Tiles
https://youtu.be/oYNA24tcYc0?si=UV5DHMMCLkoV03k0