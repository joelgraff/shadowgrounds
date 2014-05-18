Shadow Grounds OSG
=============

Shadow Grounds Shader Development Environment  (GPLv3 License)

Initial release.

--------------------
Project Status
--------------------

At present, basic interface exists, allows importing of 3D models, as well as camera manipulation using OpenSceneGraph's trackball manipulator.

Basic management of the scene graph, serialization, node transformations (translate, rotate, scale), shader uniforms also included.

Scene graph structure:

Project_root
	Project_data (serialization node)
	Scene_root
	Asset_library (models, shaders, texutres, etc.)

Scene_root node and all subnodes are rendered onscreen.  Project data node and Asset library are not rendered.

Most scene graph manipulation is limited to nodes under scene_root.

---------------------
Documentation
---------------------

parser_rules.txt contains syntax for command structure.
config.ini provides basic configuration.

See files for further info.

---------------------
Compilation
---------------------

Dependencies:

	OpenSceneGraph v.2.8.0 or greater.
	Boost 1.47 or greater (uses boost::filesystem, boost::any, and boost::spirit)

---------------------
Links / Contact
---------------------

Youtube channel:

http://www.youtube.com/user/JoelCGraff

email:
monograff76@comcast.net
