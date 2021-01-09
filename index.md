# Abstract
<p align = "justify">Robotic arms can replace manpower-driven operation for grasping and other tasks to improve the production efficiency and quality of products. Currently, deep learning-based methods are used on many robotic arms for grasping objects tasks. However, this type of methods requires a large number of samples to train the pose estimation model, which has a problem of poor generalization ability. To solve the above problems, an efficient visual-based grasping system of robotic arm by RGB-D image is built to reduce the running time of the pose acquisition algorithm, and improve positioning accuracy and the efficiency in this paper. The system uses a structure with eye-in-hand. The visual input of the Intel RealSense D435i camera is used to achieve the rapid detection and pose estimation of the target. The Robot Operating System (ROS) is used to control the motion of UR5. In this paper, we proposed a Minimum Bounding Rectangle (MinBRect) target detection algorithm. MinBRect detects the target quickly by detecting the minimum bounding rectangle. MinBRect calculates the angle of the detected rectangle to estimate the pose. Here, the grasping experiment is carried out with an actual robotic arm. The experimental results show that the proposed method is efficient and effective. In our experiment, the results of target detection and pose estimation for 7 kinds of regular and irregular objects have high accuracy. The designed grasping method is portable, and the data set does not need to be constructed, which makes the workload of the system design reduce. At the same time, it meets the demands for the rapidity of the robotic arm when performing tasks in modern factory.</p>

![Visual grasp pipeline](https://raw.githubusercontent.com/QRayMoor/MinBRect/main/IMG/visual_grasp_pipeline.svg)
<center style="font-size:14px;color:#C0C0C0;text-decoration:underline">Visual Grasp Pipeline</center>


# Experiment

### 1.Single-target grasping
- Stapler
<iframe width="833" height="470" src="https://www.youtube.com/embed/R604wt3xKkc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

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
