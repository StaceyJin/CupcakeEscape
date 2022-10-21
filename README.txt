May 11, 2021

420-N44-LA Game Development with Unity

Project - Cupcake Escape

Development Notes and references


Resources and references used to complete the game programming:


- Creating a THIRD PERSON COntroller in Unity
	https://www.youtube.com/watch?v=TnhDwCI4qqg

- How to create a Health Life System in Unity
	https://www.youtube.com/watch?v=Ay159WsGDJQ

- How to reset scene after collision
	https://forum.unity.com/threads/how-to-reset-scene-after-collision.606100/

- How to create a count down timer in C# Unity Tutotial
	https://www.youtube.com/watch?v=Qhm_t46kuM4

- Why are my UI buttons not working in Unity?
	https://www.infogamerhub.com/why-are-my-ui-buttons-not-working-in-unity/

(This video helped me solve some of the other transition/menu screen issues)


Audio Credits:

"Music by Tri-Tachyon - https://soundcloud.com/tri-tachyon/albums".

All audio files taken from https://freesound.org/.



Notable Technical Issues:

The Navmesh Agent on the Oven was difficult to adjust, with the frame being cylindrical and needing to fit a cubic body. 
I tried creating a smaller 3D object and including it as part of the Oven as a child. The frame is still raised a bit above 
the oven, and had created issues in Stage 3, where all the Ovens were hovering over the floor a good amount. That was fixed with adjusting 
Height and HeightMesh settings. This may be the reason why upon collision of the Player and Oven, there may be more than one occurence, leading
to two lives being reduced instead of one.


Edited October 21, 2022

