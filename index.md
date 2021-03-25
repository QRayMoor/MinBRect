# Abstract
<p align = "justify">Robotic manipulators can replace manpower driven operation for grasping and other tasks to improve the production efficiency and quality of products. In practice, images captured by position fixed camera like Kinect or RealSense only perceive the fixed region. After image collection, object detection and pose estimation are key steps for robotic manipulator object grasping. Many deep learning-based methods are used to estimate the target position and pose. However, this kind of methods requires a large number of samples to train the estimation model, which has a problem of poor generalization ability. To solve the above problems, an efficient visual-based grasping algorithm and system of robotic manipulator by RGB-D image is built to reduce the running time of the pose acquisition, and improve position estimation accuracy and efficiency in this paper. To perceive the dynamic region range, the system uses an eye-in-hand structure with the Intel RealSense D435i camera and UR5. To estimate the target position and pose quickly without a lot of pre-training, we proposed a Minimum Bounding Rectangle (MinBRect) target detection algorithm. MinBRect detects the target quickly by detecting the minimum bounding rectangle. MinBRect calculates the angle of the detected rectangle to estimate the pose. Here, the grasping experiment is carried out with an actual robotic manipulator. In our experiment, the results of target detection and pose estimation for 7 kinds of regular and irregular objects have high accuracy, which indicates the designed grasping method is portable. Compared with the machine learning algorithm, e.g. Linemod, our proposed algorithm has a high success rate. Moreover, there is no data set need to be constructed, which makes a significant reduction in the amount of work required for system design. At the same time, it meets the demands for the rapidity of the robotic manipulator when performing tasks in modern factory. Experiment results show that the proposed method is efficient and effective.</p>

![Visual grasp pipeline](https://raw.githubusercontent.com/QRayMoor/MinBRect/main/IMG/visual_grasp_pipeline.svg)
<center style="font-size:14px;color:#C0C0C0;text-decoration:underline">Visual Grasp Pipeline</center>


# Experiment

### 1.Single-target grasping
- Stapler
<iframe width="833" height="470" src="https://www.youtube.com/embed/R604wt3xKkc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Screwdriver
<iframe width="833" height="470" src="https://www.youtube.com/embed/BiAwhiBl8pI?list=TLPQMDkwMTIwMjGI8SH0ANHfxw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Wood Block
<iframe width="833" height="470" src="https://www.youtube.com/embed/PLx9Gx8dnz4?list=TLPQMDkwMTIwMjGI8SH0ANHfxw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Sleeve Connector
<iframe width="833" height="470" src="https://www.youtube.com/embed/CtpkClToNjU?list=TLPQMDkwMTIwMjGI8SH0ANHfxw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Box
<iframe width="833" height="470" src="https://www.youtube.com/embed/LhKf726XUX0?list=TLPQMDkwMTIwMjGI8SH0ANHfxw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- Umbrella
<iframe width="833" height="470" src="https://www.youtube.com/embed/TloC-ZAtbUk?list=TLPQMDkwMTIwMjGI8SH0ANHfxw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### 2.Multi-target grasping
<iframe width="833" height="470" src="https://www.youtube.com/embed/2FJ7A4YKRFM?list=TLPQMDkwMTIwMjGI8SH0ANHfxw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Blocked? Click [HERE](https://www.bilibili.com/video/BV1dp4y1b7te/) to see the videos.
