[![Build Status](https://travis-ci.org/CURG/pc_scene_completion_ws.svg?branch=master)](https://travis-ci.org/CURG/pc_scene_completion_ws)

# pc_scene_completion_ws
ROS scene completion workspace and external dependencies. 

## Setup
```
git clone https://github.com/CURG/pc_scene_completion_ws.git --recursive
```

Follow installation instructions found in the .travis.yml file. Specifically starting here:

https://github.com/CURG/pc_scene_completion_ws/blob/master/.travis.yml#L50

You will need to install all the libraries in the external folder, and then you can build the src folder as a ros workspace. The travis.yml script does not cover Keras installation which is well documented on the Keras site.  We run Keras with a tensorflow backend. 

## More information
Please read more about running and trouble shooting the pc_pipeline here:

https://github.com/CURG/pc_pipeline_launch


Please read more about the CNN for shape completion here:

https://github.com/CURG/pc_object_completion_cnn
