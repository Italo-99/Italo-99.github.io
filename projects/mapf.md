---
layout: default
title: Multi-Robot Coordination in Dynamic Warehouses
---

<div class="lang-switch">
  <a class="button-link" href="../projects.html">All projects</a>
  <a class="button-link" href="../it/mapf.html">Italiano</a>
</div>

# Multi-Robot Coordination for Dynamic Warehouses

<div class="project-hero-media">
  <!-- <img src="../media/mapf/mapf_sim.gif" alt="Warehouse simulation GIF"> -->
  <!-- Optional MP4 version for future tests.
  -->
  <video autoplay loop muted playsinline>
    <source src="../media/mapf/mapf_sim.mp4" type="video/mp4">
  </video>
</div>

## Project Overview

This project is the main research direction of my PhD and focuses on scalable, robust, and flexible coordination of robot fleets in dynamic warehouse environments.

I designed and developed a complete C++ simulation framework integrated with ROS2 and CoppeliaSim, with support for event-based and periodically triggered planning strategies. The goal is to study lifelong multi-robot path planning under realistic operational conditions, where goals change online, robots may experience execution errors, and the environment is not static.

## My role

This work is fully mine at the system-design and implementation level.

- Design of the software architecture
- Development of the simulation and planning framework in C++
- Integration with ROS2 and CoppeliaSim
- Research on MAPF, TAPF, and logistics-oriented decision making
- Ongoing exploration of Reinforcement Learning techniques for optimization and adaptation

## Technical highlights

- Fleet-scale simulations with up to 250 robots
- Online planning below 100 ms in dynamic scenarios
- Event-triggered and periodic replanning modes
- Dynamic goal updates and execution-aware replanning
- Ostacle avoidance and conflict management
- Modular structure for future integration of learning-based decision layers

## Why it matters

Most demonstrations of multi-robot planning look strong in controlled conditions, but become much less convincing when execution noise, asynchronous events, or changing task assignments are introduced.

My focus is on making these systems usable in settings where robustness matters as much as nominal optimality. That means building algorithms and software that keep working when the environment changes, not only when the benchmark stays clean.

<div style="text-align: center; margin: 1rem 0 0.5rem 0;">
  <img src="../media/mapf/mapf_plan.png" alt="Planning snapshot for multi-robot system" style="width: min(70%, 900px); clip-path: inset(0px 20px 20px 30px);">
</div>
<p style="text-align: center;">
  Trajectories planned on a roadmap-based warehouse environment for multiple agents.
</p>

<div style="text-align: center; margin: 1rem 0 0.5rem 0;">
  <img src="../media/mapf/mapf_coppelia.png" alt="Warehouse simulation in CoppeliaSim" style="width: min(88%, 1200px);">
</div>
<p style="text-align: center;">
  CoppeliaSim simulation of four robots in a warehouse-like environment.
</p>

## Stack

- C++
- ROS2
- CoppeliaSim
- Multi-agent path finding
- Task allocation
- Reinforcement Learning for logistics optimization

---

<a class="button-link" href="../projects.html">Back to projects</a>
