---
layout: default
title: Deformable Object Manipulation
---

<div class="lang-switch">
  <a class="button-link" href="../projects.html">All projects</a>
  <a class="button-link" href="../it/deformable.html">Italiano</a>
</div>

# Deformable Object Manipulation

This page collects my work on deformable objects, from cable perception and grasping foundations to current research on mobile manipulators and co-manipulation. The most recent activities are connected to the SiMOD project.

## <a id="bags"></a>Mobile manipulation of deformable objects

<div class="project-hero-media">
  <img src="../media/bags/MobilePlatform_SideView.jpeg" alt="Mobile manipulator platform with UR5e on Neobotix">
</div>

### Overview

Within the SiMOD project, I work on perception and manipulation pipelines for deformable objects using mobile manipulators.

One representative setup combines a UR5e arm mounted on a Neobotix MPO-500 mobile base, with an Intel RealSense D435i installed near the gripper. This enables target detection, environment perception, grasp planning, and execution in cluttered and partially occluded scenarios.

### My role

This software work is primarily mine, excluding third-party perception models explicitly referenced where needed.

- Perception and manipulation pipeline integration
- Grasp execution and task-level software logic
- System testing in simulation and on the real platform
- Extension toward physically interactive manipulation behaviors

### Technical focus

- Deformable object detection and localization
- RGB-D perception for target estimation
- Grasping of bags and soft objects on realistic surfaces
- Reactive manipulation under interaction constraints
- Integration between perception, motion, and execution control

<div class="gallery-three">
  <img src="../media/bags/bags_detection_new.png" alt="Bag detection example">
  <img src="../media/bags/bags_grasping.png" alt="Bag grasping example">
  <img src="../media/arm_rover/tiago_manipulators.png" alt="TIAGo manipulation setup">
</div>

### Related public posts

<div class="link-pills">
  <a href="https://www.linkedin.com/posts/italo-almirante-62431a216_robotics-perception-research-activity-7386056647640571905-Z9xD">Single-arm mobile manipulation post</a>
  <a href="https://www.linkedin.com/posts/italo-almirante-62431a216_mobile-manipulation-of-large-deformable-activity-7384270449653772288-xe9u">Dual-arm co-manipulation post</a>
  <a href="https://simod.eu/">SiMOD project</a>
</div>

## Co-manipulation and interaction strategy

A key aspect of this line of work is co-manipulation of large deformable objects with multiple manipulators.

The control logic is not just about tracking a shared path. One robot acts as the leader and autonomously decides the reference motion, while the second robot follows through force sensing and passive force-control behavior. This makes the system more tolerant to uncertainty in object deformation and interaction constraints, and it is especially useful when geometric shape alone is not enough to coordinate the task reliably.

## <a id="dlo"></a>DLO perception and grasping foundations

<div class="project-hero-media">
  <img src="../media/dlo/coppelia_grabbing_pose.png" alt="Cable grasping in simulation">
</div>

### Overview

This work started from my internship and master's thesis and laid the foundations for later manipulation projects.

I developed a ROS-based pipeline for handling deformable linear objects such as cables and ropes on planar surfaces. The workflow combines image-based detection, depth-based pose reconstruction, grasp execution, and validation in simulation and on the real system.

### What I developed

- ROS1 software pipeline for the full manipulation workflow
- Integration between perception, 3D estimation, and manipulator execution
- Simulation in CoppeliaSim for validation of grasp configurations
- Real-world grasping tests on cable-like objects

### Method summary

- RGB image processing for DLO detection
- 3D pose reconstruction using stereo or depth information
- Grasp and move routine for deformable linear objects on planar surfaces
- Sim-to-real comparison between modeled and physical behavior

<div class="gallery-two">
  <img src="../media/dlo/RealeDetection1.png" alt="Real cable detection image 1">
  <img src="../media/dlo/RealeDetection2.png" alt="Real cable detection image 2">
</div>

<div class="gallery-two">
  <img src="../media/dlo/real_grabbing_pose.jpg" alt="Real cable grasping pose">
  <img src="../media/dlo/coppelia_grabbing_pose.png" alt="Simulated cable grasping pose">
</div>

### Note on perception models

The cable segmentation module was based on state-of-the-art deformable linear object perception methods rather than a perception network developed by me. This site keeps that distinction explicit.

### References and related links

<div class="link-pills">
  <a href="https://lar-unibo.github.io/files/publications/FASTDLO_Fast_Deformable_Linear_Objects_Instance_Segmentation.pdf">FASTDLO paper</a>
  <a href="https://mediatum.ub.tum.de/doc/1701469/v9sewlaprnb16nt77gnt2pn8r.10045806.pdf">RT-DLO paper</a>
</div>

## Tools and platforms across this line of work

- ROS1 and ROS2
- CoppeliaSim
- RGB-D perception
- Universal Robots manipulators
- Mobile bases and integrated mobile manipulators
- Force-aware interaction control

---

<a class="button-link" href="../projects.html">Back to projects</a>
