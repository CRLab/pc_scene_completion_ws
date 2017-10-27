[![Build Status](https://travis-ci.org/CRLab/pc_scene_completion_ws.svg?branch=master)](https://travis-ci.org/CRLab/pc_scene_completion_ws)

# pc_scene_completion_ws
ROS scene completion workspace and external dependencies. This is a self contained workspace for running the pc_pipeline with the shape completion CNN. This is the workspace from the IROS 2017 paper "Shape Completion Enabled Robotic Grasping" found here:

http://shapecompletiongrasping.cs.columbia.edu/ 

and is demonstrated in the video below:

[![Shape Completion Enabled Robotic Grasping](https://img.youtube.com/vi/Dxd0ItPhh7c/0.jpg)](https://www.youtube.com/watch?v=Dxd0ItPhh7c "Shape Completion Enabled Robotic Grasping")


Please read more about running and trouble shooting the pc_pipeline here:

https://github.com/CRLab/pc_pipeline_launch


Please read more about the CNN for shape completion here:

https://github.com/CRLab/pc_object_completion_cnn

## Setup
```
git clone https://github.com/CRLab/pc_scene_completion_ws.git --recursive
```

Follow installation instructions found in the .travis.yml file. Specifically starting here:

https://github.com/CRLab/pc_scene_completion_ws/blob/master/.travis.yml#L50

You will need to install all the libraries in the external folder, and then you can build the src folder as a ros workspace. The travis.yml script does not cover Keras installation which is well documented on the Keras site.  We run Keras with a tensorflow backend. 
