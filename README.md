#Active Vision Dataset Processing

This project contains Python and MATLAB scripts for processing the
 [Active Vision Dataset](http://cs.unc.edu/~ammirato/active_vision_dataset_website/index.html)
It is an active project, with more and updated code to come.


To get started, edit the `ROHIT_BASE_PATH` variable in `run.py` and/or `init_paths.m`
to point to the directory that contains our data. i.e. the parent directory 
that the directory for each scan.

```
  ROHIT_BASE_PATH = /path/to/dataset/
```

##Running code
Everything is a function. See examples below
for how to run certain functions, or look at the README
in your directory of interest. (Currently `visualizations` 
is the only interesting one)
###Python
To run a python function from the command line:
  ```
  python run.py function_name scene_name
  ```

###MATLAB
1. Start MATLAB
2. Run `init_paths`
3. Call the desired function



#Visualizations
Use the code here to visualize our data.
###Visualize our images and bounding boxes, and virtually move around each scene.
#####Python
  ```
    python run.py vis_boxes_and_move Home_01_1 
  ``` 
#####MATLAB
  ```
    >>>vis_boxes_and_move('Home_01_1')
  ``` 


###Visualize the camera positions and directions in each scene.
#####Python
  ```
    python run.py vis_camera_pos_dirs Home_01_1 
  ``` 
#####MATLAB
  ```
    >>>vis_camera_pos_dirs('Home_01_1')
  ``` 

 Replace `Home_01_1` with whichever scene you wish to view 



 


