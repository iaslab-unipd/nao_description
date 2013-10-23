nao_description
===============

URDF Model description of Aldebaran NAO

Instructions (tested with Blender v2.66 - v2.69):
- Download nao-v4.blend
- Open the downloaded file with Blender 
- Open a Text Editor window inside Blender
- Open the io_export_separate.py script
- Run the script
- Copy the generated meshes from ~/nao_mesh/stl/ to /YOUR_CATKIN_WS/src/nao_description/mesh/stl
- Try the result using roslaunch nao_description rviz.launch
