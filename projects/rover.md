---
layout: default
title: ProjectRED Rover Systems
---

<div class="lang-switch">
  <a class="button-link" href="../projects.html">All projects</a>
  <a class="button-link" href="../it/rover.html">Italiano</a>
</div>

# ProjectRED Rover Systems

This page collects the main robotics work I carried out within ProjectRED, including technical leadership, software architecture supervision, autonomous navigation, rover manipulation, and subsystem integration.

## ProjectRED story and leadership

<div class="project-hero-media">
  <img src="../media/rover/rover.jpg" alt="ProjectRED rover">
</div>

I joined ProjectRED first as a control software developer, then served as Project Manager, and later continued as external advisor and robotics supervisor.

My contribution spans both engineering execution and leadership responsibilities.

### Leadership and coordination scope

- Team leadership for a multidisciplinary rover team
- Planning, task allocation, and technical supervision across software activities
- Budget management experience during the year in which I served as team leader
- Support to software architecture decisions and subsystem integration in later years
- Coordination between control, robotics, and system-level validation efforts

### Competition history relevant to my role

- ERC 2022 Remote: 3rd place
- ERC 2023 Remote: 3rd place
- ERC 2023 On-Site: 9th place, highest ProjectRED on-site result so far
- Team budget in my Project Manager year: more than 60k euros
- Team budgets in later years: around 30k euros

## <a id="navigation"></a>Autonomous navigation and digital twin

<div class="gallery-two">
  <img src="../media/rover/rover_unity.png" alt="Unity rover simulation">
  <img src="../media/rover/rover_marsyard.jpeg" alt="Rover in MarsYard">
</div>

### Overview

A major part of the rover work focused on autonomous navigation from simulation to field deployment.

I collaborated on the autonomous control architecture of the rover and supervised the construction of a ROS2 plus Unity digital twin used to validate navigation workflows before real-world testing.

### Technical content

- High-fidelity Unity plus ROS2 digital twin for validation and testing
- Autonomous navigation stack with real-time obstacle handling
- Localization pipeline combining wheel odometry, visual odometry, and landmark-based estimation
- Simulation-to-reality consistency checks for field deployment
- Nav2-oriented integration and custom obstacle filtering logic

<div class="gallery-two">
  <img src="../media/rover/probing_rover_unity.png" alt="Probing task in Unity">
  <img src="../media/rover/probing_rover_real.png" alt="Probing task in real environment">
</div>

<div class="link-pills">
  <a href="https://www.linkedin.com/posts/italo-almirante-62431a216_projectred-europeanroverchallenge-autonomousnavigation-activity-7388863699136094209-9TYG">Navigation post</a>
</div>

## <a id="manipulation"></a>Rover arm, probing, and deep sampling

### Overview

I also collaborated on the robotic arm subsystem and on the integration of science-oriented rover functionalities.

This includes manipulator motion, grasp execution, remote guidance for precise operations, and the coupling between field tasks and robotic control.

### Technical content

- MoveIt2-based motion routines and trajectory planning
- CANopen-oriented motor communication and subsystem coordination
- Remote teleoperation for fine motion guidance
- Probe detection and alignment support for autonomous approach
- Integration with science and sampling workflows

### Drilling and sampling subsystem

The rover platform also included an onboard drill and deep-sampling workflow. In the site structure, this is presented as a collaborative subsystem in which I contributed within a broader team context, rather than as a standalone individual project.

<div class="link-pills">
  <a href="https://www.linkedin.com/posts/italo-almirante-62431a216_projectred-europeanroverchallenge-robotics-ugcPost-7393605155243495425-uCqN">Rover arm post</a>
  <a href="https://www.linkedin.com/feed/update/urn:li:activity:7399105184318009344/">Drilling system post</a>
</div>

## Certificates and public references

<div class="link-pills">
  <a href="https://spacecert.org/certificate/25NBF9E2/">ERC 2025 certificate</a>
  <a href="https://roverchallenge.eu/certificate/projectred-italo-almirante-erc2024-on-site/">ERC 2024 on-site certificate</a>
  <a href="https://roverchallenge.eu/certificate/2023-onsite-projectred-italo-almirante/">ERC 2023 on-site certificate</a>
  <a href="https://roverchallenge.eu/certificate/2023-remote-projectred-italo-almirante/">ERC 2023 remote certificate</a>
  <a href="https://projectred.it/">ProjectRED website</a>
</div>

## Ownership note

ProjectRED is, by nature, a multidisciplinary team effort. This page reflects my actual role: strong direct contribution to robotics and control activities, leadership and coordination responsibilities, and supervision of software architecture and integration, without presenting the overall rover as an individual-only project.

---

<a class="button-link" href="../projects.html">Back to projects</a>
