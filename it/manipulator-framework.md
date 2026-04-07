---
layout: default
title: Manipulator Framework
---

<div class="lang-switch">
  <a class="button-link" href="../progetti.html">Tutti i progetti</a>
  <a class="button-link" href="../projects/manipulator-framework.html">English</a>
</div>

# Manipulator Framework

## Il progetto

Questo progetto raccoglie l'infrastruttura software che ho sviluppato ed esteso per planning e controllo di manipolatori, partendo da prototipi in ROS1 e arrivando a un'evoluzione più modulare in ROS2.

L'obiettivo non è un controller specifico per un singolo robot, ma un layer software riusabile capace di supportare manipolatori, end-effector e configurazioni di task differenti.

## Il mio ruolo

Questo lavoro si colloca tra sviluppo software personale ed estensioni collaborative realizzate in progetti robotici più ampi.

- Implementazione iniziale in ROS1 durante tesi e tirocinio
- Riuso ed estensione in contesti rover e manipulation
- Evoluzione continua verso wrapper ROS2 e maggiore modularità

## Obiettivi di progetto

- Integrazione modulare con planner
- Struttura il più possibile manipulator-agnostic
- Separazione chiara tra kinematics, execution logic e task-level control
- Riusabilità tra simulazione e sistemi reali
- Estensione più semplice verso manipolatori diversi e setup di mobile manipulation
- Supporto per cinematica diretta e inversa
- Controllo di velocità real-time in spazio cartesiano e di giunto

<div class="project-hero-media">
  <img src="../media/arm_rover/tiago_manipulators.png" alt="TIAGo manipulation architecture">
</div>

<div class="project-hero-media">
  <img src="../media/arm_rover/ur_manipulators.png" alt="UR manipulation architecture">
</div>

## Riferimento pubblico

<div class="link-pills">
  <a href="https://www.linkedin.com/posts/italo-almirante-62431a216_i-am-happy-to-share-with-you-the-latest-project-activity-7264964079721566208-cYzC">Post LinkedIn sulla repository</a>
  <a href="https://github.com/Italo-99">Profilo GitHub</a>
</div>

---

<a class="button-link" href="../progetti.html">Torna ai progetti</a>
