---
layout: default
title: Manipulator Framework
---

<div class="lang-switch">
  <a class="button-link" href="../projects.html">All projects</a>
  <a class="button-link" href="../it/manipulator-framework.html">Italiano</a>
</div>

# Manipulator Framework

## Project Overview

This project collects the software infrastructure I developed and extended for manipulator planning and control, starting from ROS1-based prototypes and evolving toward more modular ROS2-oriented architectures.

The goal is not a robot-specific controller, but a reusable software layer that can support different manipulators, end-effectors, and task configurations.

## My role

This work sits between personal software development and collaborative extensions carried out in broader robotics projects.

- Initial ROS1 implementation during thesis and internship activities
- Reuse and extension in rover and manipulation contexts
- Ongoing evolution toward ROS2 wrappers and cleaner modularity

## Design goals

- Modular planner integration
- Manipulator-agnostic software structure where possible
- Clear separation between kinematics, execution logic, and task-level control
- Reusability across simulation and real systems
- Easier extension toward different manipulators and mobile manipulation setups
- Inverse and forward kinematics support
- Real time speed control in both cartesian and joint space

<div class="project-hero-media">
  <img src="../media/arm_rover/tiago_manipulators.png" alt="TIAGo manipulation architecture">
</div>
<p style="text-align: center;">Manipulator functions menu with the TIAGo.</p>


<div class="project-hero-media">
  <img src="../media/arm_rover/ur_manipulators.png" alt="UR manipulation architecture">
</div>
<p style="text-align: center;">Manipulator functions menu with the UR.</p>

## Public reference

<div class="link-pills">
  <a href="https://www.linkedin.com/posts/italo-almirante-62431a216_i-am-happy-to-share-with-you-the-latest-project-activity-7264964079721566208-cYzC">LinkedIn post about the repository</a>
  <a href="https://github.com/Italo-99">GitHub profile</a>
</div>

---

<a class="button-link" href="../projects.html">Back to projects</a>
