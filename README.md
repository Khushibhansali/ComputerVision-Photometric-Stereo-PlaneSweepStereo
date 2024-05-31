# Photometric Stereo & Plane Sweep Stereo

The primary objective of this project was to recover the surface geometry and material properties from photographs. In the context of photometric stereo, our efforts were directed towards stacking multiple images captured from a consistent viewpoint but illuminated by different known light sources. This technique allowed us to extract the albedo and surface normals of the object, providing detailed information about its texture and shape.

In addition to photometric stereo, we implemented plane sweep stereo. For this approach, we utilized two calibrated images of the same scene, each taken from a slightly different viewpoint. By carefully analyzing the disparities between these images, we were able to generate a rough depth map, which served as a preliminary representation of the scene's 3D structure.

Finally, we focused on depth map reconstruction. This step involved refining the rough depth map to create a more accurate 3D mesh of the scene. By integrating data from the depth map and further processing, we were able to reconstruct a detailed and precise 3D model, showcasing the intricate details of the object's geometry.

Throughout the project, we encountered and overcame various challenges, such as ensuring accurate calibration, dealing with noise in the images, and optimizing algorithms for better performance. The integration of these techniques provided a comprehensive approach to 3D reconstruction, combining photometric stereo and plane sweep stereo to achieve a robust and detailed representation of the object's surface.
