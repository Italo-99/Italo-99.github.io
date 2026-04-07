---
layout: default
title: Italo Almirante - Italiano
---

<!-- Home page (Italiano) -->

<div class="lang-switch">
  <a class="button-link button-link-primary" href="./index.html">English</a>
  <a class="button-link" href="./progetti.html">Progetti</a>
  <a class="button-link" href="./novita.html">Novità</a>
  <a class="button-link" href="./pubblicazioni.html">Pubblicazioni</a>
</div>

<section class="hero-grid">
  <div>
    <h1 class="hero-title">Italo Almirante</h1>
    <p class="hero-subtitle">PhD Researcher in Robotics</p>
    <p class="hero-text">
      Progetto e sviluppo applicazioni per il controllo di sistemi robotici, dal controllo embedded e i layer di comunicazione fino a navigazione autonoma, manipolazione, simulazione e coordinamento del traffico multi-robot.
    </p>
    <p class="hero-text">
      Il mio lavoro comprende integrazione di sistema e ricerca sull'autonomia di robot industriali e outdoor, con particolare attenzione a coordinamento di flotte, mobile manipulation, e space robotics.
    </p>
    <div class="hero-actions">
      <a class="button-link button-link-primary" href="./progetti.html">Esplora i progetti</a>
      <a class="button-link" href="./novita.html">Aggiornamenti</a>
    </div>
  </div>
  <div class="hero-photo-wrap">
    <img class="hero-photo" src="./media/Italo-99_picture.jpg" alt="Ritratto di Italo Almirante">
  </div>
</section>

## Di cosa mi occupo

<div class="feature-grid">
  <div class="feature-card">
    <h3>Autonomia multi-robot</h3>
    <p>Pianificazione scalabile, coordinamento di flotte e framework di simulazione per scenari logistici dinamici.</p>
  </div>
  <div class="feature-card">
    <h3>Mobile manipulation</h3>
    <p>Manipolazione di oggetti deformabili guidata da: percezione 3D, interazione con controllo di forza e architetture software riusabili e modulari.</p>
  </div>
  <div class="feature-card">
    <h3>Space robotics systems</h3>
    <p>Prototipi di rover autonomi, con bracci robotici e sottosistemi per l'analisi scientifica,
        l'esplorazione e la navigazione autonoma.</p>
  </div>
</div>

## Progetti in evidenza

<div class="project-grid project-grid-3">
  <a class="project-card" href="./it/mapf.html">
    <img src="./media/mapf/mapf_sim.gif" alt="GIF simulazione MAPF warehouse">
    <div class="project-card-body">
      <p class="card-kicker">Ricerca</p>
      <h3>Multi-Robot Planning</h3>
      <p>Framework in C++ e ROS2 per coordinamento di flotte e autonomia robusta.</p>
    </div>
  </a>

  <a class="project-card" href="./it/deformable.html#bags">
    <img src="./media/bags/bags_grasping.png" alt="Manipolazione di sacchi deformabili">
    <div class="project-card-body">
      <p class="card-kicker">Ricerca</p>
      <h3>Manipolazione di oggetti deformabili</h3>
      <p>Percezione, grasping, co-manipolazione e interazione con manipulatori mobili con controlli a feedback di forza.</p>
    </div>
  </a>

  <a class="project-card" href="./it/deformable.html#dlo">
    <img src="./media/dlo/real_grabbing_pose.jpg" alt="Setup di presa su cavo">
    <div class="project-card-body">
      <p class="card-kicker">Ricerca</p>
      <h3>DLO Perception and Grasping</h3>
      <p>Segmentazione di cavi, stima della posa 3D, validazione in CoppeliaSim ed esecuzione sim-to-real.</p>
    </div>
  </a>

  <a class="project-card" href="./it/rover.html#navigation">
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
      <h3>Navigazione autonoma e digital twin</h3>
      <p>Autonomous navigation, localizzazione, gestione ostacoli e workflow ROS2-Unity.</p>
    </div>
  </a>

  <a class="project-card" href="./it/rover.html#manipulation">
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
      <h3>Braccio rover e sampling</h3>
      <p>Controllo del manipolatore, probing, deep sampling e integrazione di sottosistemi per applicazioni outdoor.</p>
    </div>
  </a>

  <a class="project-card" href="./it/manipulator-framework.html">
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
      <p>Software riusabile per pianificazione e controllo di manipolatori commerciali e custom.</p>
    </div>
  </a>
</div>

## Profilo ingegneristico

<!-- <div class="metrics-row">
  <div class="metric-card">
    <strong>250+</strong>
    <span>robot gestiti in simulazione warehouse</span>
  </div>
  <div class="metric-card">
    <strong>&lt; 100 ms</strong>
    <span>target di replanning in scenari dinamici</span>
  </div>
  <div class="metric-card">
    <strong>Full stack</strong>
    <span>embedded, controllo, percezione, planning, simulazione</span>
  </div>
</div> -->

<div class="stack-grid">
  <div>
    <h3>Domini principali</h3>
    <ul>
      <li>Coordinamento multi-agent e multi-robot</li>
      <li>Manipolazione robotica "soft"</li>
      <li>Navigazione autonoma e digital twin</li>
      <li>Robotica guidata da visione e AI</li>
    </ul>
  </div>
  <div>
    <h3>Strumenti principali</h3>
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

## Esplora il sito

<div class="feature-grid">
  <div class="feature-card">
    <h3><a href="./progetti.html">Progetti</a></h3>
    <p>Pagine dettagliate su ricerca, software e sistemi robotici integrati.</p>
  </div>
  <div class="feature-card">
    <h3><a href="./pubblicazioni.html">Pubblicazioni</a></h3>
    <p>Una sezione oer articoli scientifici, output di ricerca e riferimenti tecnici.</p>
  </div>
  <div class="feature-card">
    <h3><a href="./novita.html">Novità e aggiornamenti</a></h3>
    <p>Uno spazio dedicato a future news, milestone, opportunità e annunci.</p>
  </div>
</div>

---

## Link

<div class="link-pills">
  <a href="https://www.linkedin.com/in/italo-almirante-62431a216/">LinkedIn</a>
  <a href="https://github.com/Italo-99">GitHub</a>
  <a href="https://scholar.google.com/citations?user=Ap9R8foAAAAJ">Google Scholar</a>
  <a href="https://www.arscontrol.unimore.it/italo-almirante/">ARS Control Lab</a>
  <!-- <a href="https://projectred.it/">ProjectRED</a> -->
  <a href="https://www.dismi.unimore.it/it/didattica/progetti-gli-studenti/project-red">ProjectRED</a>
</div>
