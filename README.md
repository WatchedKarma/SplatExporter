# SplatExporter
This addon make camera and rendering rig set witch make and save data in colmap file structure for 3D plat training. I Manly useing Litch field studio with that.

recomend to use with Litchfield studio, I use older build version.

Tutorial: https://youtu.be/9Hm258qzFM0

Addon appeare in N-panel as a COLMAP
Addon create camera rig
Rings with cameras. You can chose how many rings and how many cameras
Top adn bottom one have separate controls
Also it ad pole cameras witch aim on model straigth from top and bottom witch have also separate controls
You can also chose focal length of cameras
You also can switch off top, bottom, topl pole, bottom pole or all at once rings. for use with terrain
  I am planning to add more shapes for camerasbut now it contains only ring setup
If you are not satisfied with result just change parameters and addon delete cameras and make new one by the new setting
Addon needs to chose model on witch will cameras looks and aslo main part of model for pointcloud(for better results)
You can export only pointcloud but than you can use simply .ply or only cameras
It also can be used for batch rendering without other data, addon allows you to control withc engine you use and turn on transaprency for bg from the panel.

When you click on export data set blender start render every camera so it will need some time. Personally i use evee with rtx for that cuz of speed.


Personally I recomend to use 4 rings with prety small distance from model, cuz it reduce the background color witch in my cases after 15K iterations in lithcfiled started to make bugs if yoyr model was too small in camera.
My test splats: https://superspl.at/scene/033c6e41

Hope this helpe you to turn your models in to the splats as fast and simple as possible.


