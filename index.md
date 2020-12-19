# Abstract
<p align = "justify">Robotic arms can replace manpower for grasping and other tasks to improve the production efficiency and quality of products. Currently, a large number of robotic arms use the methods based on deep learning for grasping objects tasks. However, this type of methods require a large number of samples to train the model, and there is the problem of poor model portability. To solve the above problems, reduce the algorithm time of grasping pose acquisition, and improve targeting accuracy and the efficiency, this paper builds an efficient visual grasping system of robotic arm based on RGB-D image. The system uses a hand-eye structure with eyes on the hand. The visual input is based on the Intel RealSense D435i camera to achieve the rapid detection and pose estimation of the target. The Robot Operating System (ROS) is used to control the motion of the six degree of freedom (DoF) ur5 to achieve trajectory planning and target capture. We have proposed a Minimum Bounding Rectangle (MinBRect) target detection algorithm based on RGB-D images, which detects the target quickly by detecting the minimum bounding rectangle, and calculates the short axis angle of this rectangle to estimate the pose of the target. In this paper, the grasping experiment is carried out with an actual robotic arm. The experimental results show that the proposed method is simple and effective. The results of target detection and pose estimation for 7 kinds of regular and irregular objects have high accuracy. The designed grasping method has the advantage of portability, and does not need to build a huge data set, which reduces the workload of system design and satisfies the requirements for speed in modern factories.</p>

![Visual grasp pipeline](https://raw.githubusercontent.com/QRayMoor/MinBRect/main/IMG/visual_grasp_pipeline.svg)
<center style="font-size:14px;color:#C0C0C0;text-decoration:underline">Visual Grasp Pipeline</center>


# Experiment

### 1.Single-target grasping
- Stapler
<iframe width="833" height="470" src="https://www.youtube.com/embed/V4QIez8l8vc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Screwdriver
<iframe width="833" height="470" src="https://www.youtube.com/embed/csaJkbRtMBg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Wood Block
<iframe width="833" height="470" src="https://www.youtube.com/embed/rDq1iqHI5a0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Sleeve Connector
<iframe width="833" height="470" src="https://www.youtube.com/embed/8iey24X1Qbc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- 

### 2.Multi-target grasping

<iframe width="833" height="470" src="https://www.youtube.com/embed/ApaOWrdOk-Q" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# *网页仍在建设中...*
- [Abstract](#abstract)
- [Experiment](#experiment)
    + [1.Single-target grasping](#1single-target-grasping)
    + [2.Multi-target grasping](#2multi-target-grasping)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>
