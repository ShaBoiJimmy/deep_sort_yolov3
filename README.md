
# Introduction
  A special thanks to these projects. This project is to have an Ubuntu 16.04 Desktop and/or Jetpack 3.3 Nvidia JETSON TX2 to run Deep Sort with YOLOv3.

  https://github.com/nwojke/deep_sort
  
  https://github.com/qqwweee/keras-yolo3
  
  https://github.com/Qidian213/deep_sort_yolov3
  
  https://github.com/Qidian213/deep_sort_yolov3

# Getting Started

1. Download yolov3-tiny.weights and yolov3-tiny.cfg from the [YOLO website](https://pjreddie.com/darknet/yolo/). Place the weight file in the **weights** folder and the config file in the **cfg** folder in the project driectory.

2. Convert the YOLOv3-tiny weights to a Keras model. To convert run the following command:
   ```
   python convert.py cfg/yolov3-tiny.cfg weights/yolov3-tiny.weights model_data/yolo.h5
   ```
3. Run the demo with command:
   ```
   python3 demo.py
   ```

# Dependencies

  The code is compatible Python 3. The following dependencies are needed to run the tracker:

    NumPy
    scikit learn
    OpenCV

  Additionally, this project requires TensorFlow-1.4.0+.
  
# Dependencies Setup on the JETSON TX2
  
  For the JETSON TX2, you are not able to install some of the dependencies by using **pip** so you need to install from souces.
  
  1) Here is the [link](https://scikit-learn.org/stable/developers/advanced_installation.html) to install scikit learn from sources. 
 

