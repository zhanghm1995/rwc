# Resources With Code

This work is a collection of resources with code, inspired by [pwc](https://github.com/zziz/pwc), which is a splendid repository to collect  **papers with code** according to different years. 

In contrast, this project mainly focuses on resources about **environment perception**  technologies in  **autonomous vehicle** field, especially about the **lidar**, **vision**, or **sensors fusion** related algorithms.

These resources are sorted by different **perception** tasks and will be updated regularly. This repository conforms the principle **"not much, but good"**, involves the **excellent** resources including **papers, websits, researchers and so on.**

If you have any questions, welcome to open issues to contact me. Hope for this project would help for your study and research.

## Table of Contents
- [Lidar](#lidar)
  - [Segmentation & Clustering](#Segmentation-&-Clustering)
  - [Features Extraction](#Features-Extraction)
  - [Object Detection](#Object-Detection)
- [Vision](#Vision)
  - [Single Object Tracking](#Single-Object-Tracking)
  - [MOT](#MOT)
- [Sensors Fusion](#sensors-fusion)
  - [Lidar Camera Calibration](#Lidar-Camera-Calibration)
  - [Object Tracking](#Object-Tracking)
- [Researchers](#Researchers)

## Lidar

### Segmentation & Clustering
* depth clustering [[Paper]](http://www.ipb.uni-bonn.de/pdfs/bogoslavskyi16pfg.pdf) [[Code]](https://github.com/PRBonn/depth_clustering)
  * I. Bogoslavskyi and C. Stachniss. Efficient Online Segmentation for Sparse 3D Laser Scans. 2017.
- linefit_ground_segmentation [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=5548059) [[Code]](https://github.com/lorenwel/linefit_ground_segmentation)
  * Himmelsbach, Michael and Hundelshausen, Felix V and Wuensche, H-J. Fast segmentation of 3d point clouds for ground vehicles. IV, 2010.

### Features Extraction
- PointCNN [[Paper]](http://arxiv.org/abs/1801.07791) [[Code]](https://github.com/yangyanli/PointCNN)
  * Yangyan Li, Rui Bu, Mingchao Sun, Wei Wu, Xinhan Di, and Baoquan Chen. PointCNN: Convolution On X-Transformed Points. NIPS, 2018.

### Object Detection
- PointPillars [[Paper]](https://arxiv.org/abs/1812.05784) [[Code]](https://github.com/nutonomy/second.pytorch)
  * A. Lang, S. Vora, H. Caesar, L. Zhou, J. Yang and O. Beijbom: PointPillars: Fast Encoders for Object Detection from Point Clouds. CVPR 2019.
- PointRCNN [[Paper]](https://arxiv.org/abs/1812.04244) [[Code(Unavailable)]](https://github.com/sshaoshuai/PointRCNN)
  * S. Shi, X. Wang and H. Li. PointRCNN: 3D Object Proposal Generation and Detection from Point Cloud. CVPR 2019.

## Vision

### Single Object Tracking
- GOTURN [[Paper]](http://davheld.github.io/GOTURN/GOTURN.pdf) [[Code]](https://github.com/davheld/GOTURN) [[Project Page]](http://davheld.github.io/GOTURN/GOTURN.html)
  * David Held, Sebastian Thrun, Silvio Savarese. Learning to Track at 100 FPS with Deep Regression Networks. ECCV, 2016.
- ROLO---Recurrent YOLO for object tracking. [[Paper]](http://arxiv.org/abs/1607.05781) [[Code]](https://github.com/Guanghan/ROLO) [[Project Page]](http://guanghan.info/projects/ROLO/)
  * Ning, Guanghan and Zhang, Zhi et. al.. Spatially Supervised Recurrent Convolutional Neural Networks for Visual Object Tracking. arXiv, 2016.

### MOT
- deep_sort [[Paper]](https://arxiv.org/abs/1703.07402) [[Code]](https://github.com/nwojke/deep_sort)
  * Wojke, Nicolai and Bewley, Alex and Paulus, Dietrich. Simple Online and Realtime Tracking with a Deep Association Metric. ICIP, 2017.
- MDP_Tracking - (MDP=Markov Decision Processes) [[Paper]](http://cvgl.stanford.edu/papers/xiang_iccv15.pdf) [[Code]](https://github.com/yuxng/MDP_Tracking)
  * Yu Xiang, Alexandre Alahi, Silvio Savarese, Stanford University. Learning to Track: Online Multi-Object Tracking by Decision Making. ICCV, 2015.
- RNN Tracking [[Paper]](https://arxiv.org/abs/1604.03635) [[Code]](https://bitbucket.org/amilan/rnntracking/overview)
  * Anton Milan, Seyed Hamid Rezatofighi et.al.. Online Multi-Target Tracking Using Recurrent Neural Networks. AAAI, 2017.
- Nice Github Repository about **multi-object tracking using deep learning method** with codes. [[Project Page]](https://github.com/freescar/deep-multi-object-tracking-CODE#deep-multi-object-tracking-code)

## Sensors Fusion

### Lidar Camera Calibration
- ROS package to calibrate a camera and a LiDAR [[Paper]](http://arxiv.org/abs/1705.09785) [[Code]](https://github.com/ankitdhall/lidar_camera_calibration)
  * Ankit Dhall, Kunal Chelani, et. al. LiDAR-Camera Calibration using 3D-3D Point correspondences. 2017.

### Object Tracking
- precision tracking [[Paper]](http://driving.stanford.edu/papers/ICRA2013.pdf) [[Code]](https://github.com/davheld/precision-tracking)
  * David Held, Jesse Levinson, Sebastian Thrun. Precision Tracking with Sparse 3D and Dense Color 2D Data. International Conference on Robotics and Automation (ICRA), 2013.

## Researchers 
All researchers list here have offered lots of source code or greatly active in those fields listed above. It maybe have repetition with resources above, but it's still useful to know these researchers directly.
- Guanghan Ning [[Home Page]](http://guanghan.info/) [[Github]](https://github.com/Guanghan)
  * **Description:** My research is focused on computer vision and deep learning. Specifically, I'm interested in generic object detection and recognition, visual object tracking, human pose estimation and tracking.