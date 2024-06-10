# Synthetic dataset generation
Synthetic datasets play a pivotal role in computer vision, particularly in training deep learning models. Leveraging 3D computer graphics software like Blender, these datasets emulate real-world scenarios, offering images from simulated camera perspectives akin to those of actual robots. Annotations are provided for objects targeted for recognition by the robot. This approach mitigates the challenges of costly and time-intensive data collection associated with traditional methods. By harnessing virtual environments, various parameters such as surfaces, lighting conditions, environmental factors, and object colors can be effortlessly manipulated to generate diverse and annotated datasets efficiently.

# Prerequisite
Windows/Linux Blender >= 4.0

# Installation instruction:
1. Download and extract the provided folder.
2. Launch Blender and open the "cavity_ws.blend" file located inside the extracted folder.
3. In the script, navigate to lines 42 and 71, then update the directory path to "$(folder directory)/Blender-synthetic-dataset-main/...".
4. Press 'Alt + P' or use the 'Run Script' button to execute the code, loading images from the 'texture/load' folder.
5. Modify line 41 by changing the value of 'load_image_texture' from 1 to 0.
6. Run the script again to generate the Synthetic dataset.
7. The dataset will be generated within the "$(folder directory)/Blender-synthetic-dataset-main/annotation" folder.
