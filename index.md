---
layout: default
title: Italo Almirante
---

<!--
  Home page (English)
  Notes:
  - Keep this page short and visual.
  - Detailed technical content lives in /projects/*.md.
  - Cards can be duplicated or reordered without touching the overall layout.
-->

<div class="lang-switch">
  <a class="button-link" href="./it.html">Italiano</a>
  <a class="button-link" href="./projects.html">Projects</a>
  <a class="button-link" href="./news.html">News</a>
  <a class="button-link" href="./publications.html">Publications</a>
</div>

<section class="hero-grid">
  <div>
    <h1 class="hero-title">Italo Almirante</h1>
    <p class="hero-subtitle">PhD Researcher in Robotics</p>
    <p class="hero-text">
      I design and build control applications for robotic systems across the full engineering stack, from embedded control and communication layers to autonomous navigation, manipulation, simulation, and multi-robot traffic coordination.
    </p>
    <p class="hero-text">
      My work combines hands-on engineering, system integration, and research on robust autonomy for industrial and field robotics, with a strong focus on warehouse coordination, mobile manipulation, and space robotics.
    </p>
    <div class="hero-actions">
      <a class="button-link button-link-primary" href="./projects.html">Explore projects</a>
      <a class="button-link" href="./news.html">Research updates</a>
    </div>
  </div>
  <div class="hero-photo-wrap">
    <img class="hero-photo" src="./media/Italo-99_picture.jpg" alt="Italo Almirante portrait">
  </div>
</section>

## What I work on

<div class="feature-grid">
  <div class="feature-card">
    <h3>Multi-robot autonomy</h3>
    <p>Scalable planning, fleet coordination, and simulation frameworks for dynamic warehouse scenarios.</p>
  </div>
  <div class="feature-card">
    <h3>Mobile manipulation</h3>
    <p>Perception-driven manipulation of deformable objects, force-aware interaction, and modular
        and reusable manipulation software architectures.</p>
  </div>
  <div class="feature-card">
    <h3>Space robotics systems</h3>
    <p>Autonomous rover prototypes, with robotic arms and sub-systems for scientific analyses,
       autonomous exploration and navigation.</p>
  </div>
</div>

## Selected project highlights

<!--
  Home cards are teasers only.
  Detailed technical descriptions are intentionally moved to secondary pages.
-->
<div class="project-grid project-grid-3">
  <a class="project-card" href="./projects/mapf.html">
    <img src="./media/mapf/mapf_sim.gif" alt="MAPF warehouse simulation GIF">
    <!-- Optional MP4 version, kept here for future comparison.
    <video autoplay loop muted playsinline>
      <source src="./media/mapf/mapf_sim.mp4" type="video/mp4">
    </video>
    -->
    <div class="project-card-body">
      <p class="card-kicker">Research</p>
      <h3>Multi-Robot Planning</h3>
      <p>C++ and ROS2 framework for large-scale warehouse coordination, and robust autonomy.</p>
    </div>
  </a>

  <a class="project-card" href="./projects/deformable.html#bags">
    <img src="./media/bags/bags_grasping.png" alt="Mobile manipulation of deformable bags">
    <div class="project-card-body">
      <p class="card-kicker">Research</p>
      <h3>Deformable Object Manipulation</h3>
      <p>Perception, grasping, co-manipulation, and force-aware interaction with mobile manipulators.</p>
    </div>
  </a>

  <a class="project-card" href="./projects/deformable.html#dlo">
    <img src="./media/dlo/real_grabbing_pose.jpg" alt="Cable grasping setup">
    <div class="project-card-body">
      <p class="card-kicker">Research</p>
      <h3>DLO Perception and Grasping</h3>
      <p>ROS-based cable segmentation, 3D pose estimation, CoppeliaSim validation, and sim-to-real grasp execution.</p>
    </div>
  </a>

  <a class="project-card" href="./projects/rover.html#navigation">
  <div style="width:100%; height:220px; overflow:hidden;">
    <img src="./media/rover/probing_rover_unity.png"
        alt="Unity digital twin of rover"
        style="
          width:100%;
          height:85%;
          object-fit:cover;
          transform: scale(1.7) translateX(20%);
          transform-origin: center;
        ">
  </div>
    <div class="project-card-body">
      <p class="card-kicker">ProjectRED</p>
      <h3>Rover Navigation and Digital Twin</h3>
      <p>Autonomous navigation, localization, obstacle avoidance, and ROS2-Unity simulation workflows.</p>
    </div>
  </a>

  <a class="project-card" href="./projects/rover.html#manipulation">
    <div style="width:100%; height:220px; overflow:hidden;">
      <img src="./media/rover/rover.jpg"
          alt="Rover robotic arm probing task"
          style="
            width:100%;
            height:100%;
            object-fit:fit;
            transform: scale(1.0) translateX(0%);
            transform-origin: center;
          ">
    </div>
    <div class="project-card-body">
      <p class="card-kicker">ProjectRED</p>
      <h3>Rover Arm and Sampling</h3>
      <p>Manipulator control, probing, deep sampling, subsystem integration, and field-oriented robotic engineering.</p>
    </div>
  </a>

  <a class="project-card" href="./projects/manipulator-framework.html">
    <div style="width:250%; height:220px; overflow:hidden;">
      <img src="./media/arm_rover/ur_manipulators.png"
          alt="Manipulator framework teaser"
          style="
            width:100%;
            height:150%;
            object-fit:cover;
            transform: scale(1.1) translateX(-50%);
            transform-origin: 150% 250%;
          ">
    </div>
    <div class="project-card-body">
      <p class="card-kicker">Software</p>
      <h3>Manipulators Framework</h3>
      <p>Reusable planning and control software for commercial and custom manipulators.</p>
    </div>
  </a>
</div>

## Engineering profile

<!--
<div class="metrics-row">
  <div class="metric-card">
    <strong>250+</strong>
    <span>robots handled in warehouse-scale simulation</span>
  </div>
  <div class="metric-card">
    <strong>&lt; 100 ms</strong>
    <span>replanning target in dynamic fleet scenarios</span>
  </div>
  <div class="metric-card">
    <strong>Full stack</strong>
    <span>embedded, control, perception, planning, simulation</span>
  </div>
</div> -->

<div class="stack-grid">
  <div>
    <h3>Core domains</h3>
    <ul>
      <li>Multi-agent and multi-robot coordination</li>
      <li>Robotic soft manipulation</li>
      <li>Autonomous navigation and digital twins</li>
      <li>Perception-driven robotics and AI integration</li>
    </ul>
  </div>
  <div>
    <h3>Main tools</h3>
    <ul>
      <li>ROS1, ROS2, MoveIt, Nav2</li>
      <li>C++, Python, MATLAB, RobotStudio</li>
      <li>CoppeliaSim, Unity, Gazebo, MuJoCo</li>
      <li>RGB-D perception (RealSense, Zed2)</li>
      <li>Computer Vision (YOLO, SAM)</li>
      <li>Robotics platforms (Neobotics, MiR, UR)</li>
      <li>STM32, CAN, CANopen, USART/UART</li>
    </ul>
  </div>
</div>

## Explore the site

<div class="feature-grid">
  <div class="feature-card">
    <h3><a href="./projects.html">Projects</a></h3>
    <p>Detailed pages about research, software, and integrated robotic systems.</p>
  </div>
  <div class="feature-card">
    <h3><a href="./publications.html">Publications</a></h3>
    <p>A section for scientific papers, research outputs, and technical references.</p>
  </div>
  <div class="feature-card">
    <h3><a href="./news.html">News and updates</a></h3>
    <p>A dedicated page for future research notes, milestones, opportunities, and announcements.</p>
  </div>
</div>

---

## Links

<div class="link-pills">
  <a href="https://www.linkedin.com/in/italo-almirante-62431a216/">LinkedIn</a>
  <a href="https://github.com/Italo-99">GitHub</a>
  <a href="https://scholar.google.com/citations?user=Ap9R8foAAAAJ">Google Scholar</a>
  <a href="https://www.arscontrol.unimore.it/italo-almirante/">ARS Control Lab</a>
  <!-- <a href="https://projectred.it/">ProjectRED</a> -->
  <a href="https://www.dismi.unimore.it/it/didattica/progetti-gli-studenti/project-red">ProjectRED</a>
</div>
