---
layout: default
title: Coordinamento Multi-Robot
---

<div class="lang-switch">
  <a class="button-link" href="../progetti.html">Tutti i progetti</a>
  <a class="button-link" href="../projects/mapf.html">English</a>
</div>

# Coordinamento Multi-Robot in Scenari Logistici Dinamici

<div class="project-hero-media">
  <!-- <img src="../media/mapf/mapf_sim.gif" alt="GIF simulazione warehouse"> -->
  <!-- Optional MP4 version for future tests.-->
  <video autoplay loop muted playsinline>
    <source src="../media/mapf/mapf_sim.mp4" type="video/mp4">
  </video>
</div>

## Il progetto

Questo progetto rappresenta la principale direzione di ricerca del mio PhD e si concentra sul coordinamento scalabile, robusto e flessibile di flotte robotiche in ambienti warehouse dinamici.

Ho progettato e sviluppato un framework completo in C++ integrato con ROS2 e CoppeliaSim, con supporto a strategie di pianificazione event-based e periodiche. L'obiettivo è studiare il coordinamento multi-robot in condizioni operative realistiche, dove i goal cambiano online, i robot possono subire errori di esecuzione e l'ambiente non è statico.

## Il mio ruolo

Questo lavoro è interamente mio sul piano della progettazione di sistema e dell'implementazione.

- Progettazione dell'architettura software
- Sviluppo del framework di simulazione e planning in C++
- Integrazione con ROS2 e CoppeliaSim
- Ricerca su MAPF, TAPF e decision making per la logistica
- Esplorazione di tecniche di Reinforcement Learning per ottimizzazione e adattamento

## Elementi tecnici principali

- Simulazioni di flotte con oltre 250 robot
- Online planning sotto i 100 ms in scenari dinamici
- Modalità di ripianificazione event-triggered e periodica
- Aggiornamento dinamico dei goal e replanning execution-aware
- Gestione di conflitti e ostacoli
- Struttura modulare per futura integrazione di layer decisionali learning-based

<div style="text-align: center; margin: 1rem 0 0.5rem 0;">
  <img src="../media/mapf/mapf_plan.png" alt="Snapshot del planning multi-robot" style="width: min(70%, 900px);
          clip-path: inset(30px 20px 20px 30px);">
</div>
<p style="text-align: center;">
  Traiettorie pianificate su un ambiente warehouse basato su roadmap per agenti multipli.
</p>

<div style="text-align: center; margin: 1rem 0 0.5rem 0;">
  <img src="../media/mapf/mapf_coppelia.png" alt="Simulazione warehouse in CoppeliaSim" style="width: min(88%, 1200px);">
</div>
<p style="text-align: center;">
  Simulazione in CoppeliaSim di quattro robot in un ambiente di tipo warehouse.
</p>

## Stack

- C++
- ROS2
- CoppeliaSim
- Multi-agent path finding
- Task allocation
- Reinforcement Learning per ottimizzazione logistica

---

<a class="button-link" href="../progetti.html">Torna ai progetti</a>
