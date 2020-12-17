# Abstract
At present, a large number of manipulators use deep learning method to grasp a specific object. However, this kind of method needs a large number of samples to train the model, and there is a problem of poor model portability. In order to solve the above problems, reduce the time of grasping pose acquisition algorithm, improve the accuracy of target positioning, and improve the work efficiency, an efficient visual grasping system of manipulator based on rgbd is built in this paper. The system realizes the motion control of UR5 based on the robot operating system (ROS) by hand eye combination, and realizes the fast positioning and pose estimation of the target based on Intel realsense d435i, so as to realize the target grabbing. In addition, a minbrect (minimum bounding rectangle) target detection algorithm based on rgbd image is proposed. The target is detected quickly by detecting the minimum bounding rectangle, and the pose of the target is estimated by calculating the short axis angle of the minimum bounding rectangle. In this paper, the simulation experiments of rviz and gazebo are carried out by moveit! Software, and the corresponding experiments are carried out with the actual manipulator. The experimental results show that the proposed method is simple and effective, and the accuracy of target location and pose estimation for seven kinds of regular and irregular objects is high. The designed grabbing method has the advantage of portability, and it does not need to build a huge data set, which reduces the workload of system design and saves the time of grasping task.
![Visual grasp flow chart](https://github.com/QRayMoor/MinBRect/blob/main/Images/Visual%20grasp%20flow%20chart.jpg)


# Experiment

## 1.Single-target grasping

[![Grasp_1](https://res.cloudinary.com/marcomontalbano/image/upload/v1608188630/video_to_markdown/images/youtube--V4QIez8l8vc-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/V4QIez8l8vc "Grasp_1")

## 2.Multi-target grasping

[![Grasp_1](https://res.cloudinary.com/marcomontalbano/image/upload/v1608188630/video_to_markdown/images/youtube--V4QIez8l8vc-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/V4QIez8l8vc "Grasp_1")


### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/QRayMoor/MinBRect/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
