# Abstract
Robotic arms can replace manpower for grasping and other tasks to improve product production efficiency and product quality. At present, a large number of robotic arms use deep learning-based methods to grasp specific objects. However, such methods require a large number of sample training models. At the same time, there is the problem of poor model portability. In order to solve the above problems, reduce the time of capturing the pose acquisition algorithm, improve the accuracy of target positioning, and improve work efficiency, this paper builds a set of RGBD-based high-efficiency visual grasping system for robotic arms. The system adopts a hand-eye structure with eyes on the hand. The visual input is based on the Intel Realsense D435i camera to complete the rapid positioning and pose estimation of the target. Based on the ROS (Robot Operating System) robot operating system, the six-degree-of-freedom manipulator ur5 is used for motion control. Realize trajectory planning and target capture. This paper proposes a MinBRect (Minimum bounding rectangle, MinBRect) target detection algorithm based on RGBD images, which detects the target quickly by detecting the minimum bounding rectangle, and calculates the short axis angle of the minimum bounding rectangle to realize the pose estimation of the target object. This article combines the actual mechanical arm to carry out the grasping experiment. The experimental results show that the proposed method is simple and effective, and the accuracy of target positioning and pose estimation for 7 kinds of regular and irregular objects is high. The designed grasping method has the advantage of portability and does not need to build huge data. It reduces the workload of system design and satisfies the demand for speed when the robotic arm performs tasks in modern factories.

![Visual grasp pipeline](https://raw.githubusercontent.com/QRayMoor/MinBRect/main/IMG/visual_grasp_pipeline.svg)


# Experiment

### 1.Single-target grasping
- Stapler
<iframe width="739" height="417" src="https://www.youtube.com/embed/V4QIez8l8vc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Screwdriver
<iframe width="739" height"=417" src="https://www.youtube.com/embed/csaJkbRtMBg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### 2.Multi-target grasping
<iframe width="739" height="417" src="https://www.youtube.com/embed/V4QIez8l8vc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# *网页仍在建设中...*

