# UnityGlassShader
![image](https://user-images.githubusercontent.com/6388730/164811036-e939eca4-5caa-416e-bf89-a6b8545ecf98.png)

Demo Video:

https://user-images.githubusercontent.com/6388730/164812584-ad6ec20a-e746-4cfd-903b-482c7897dbc3.mp4

Materal parameters:

https://user-images.githubusercontent.com/6388730/164812290-ff3383eb-912d-46c4-8af5-47fbe58beaf7.mp4

Installation:
- Make sure Opaque texture is checked in your Universal render pipeline asset.
- Clone this repo and put it into your project.
- Use glass material or create your own material from "GlassShader" shadergraph file.
- Assign material to your object

Features:
- Tint color
- Metalic and smoothness
- Normal strenght
- Distortion tiling
- Reflection strenght
- Distort strenght

This shader does not: 
- No refraction and only distorts behind the glass.
- No multiple glass on top of each other. (whould be nice if you know how to implement)
