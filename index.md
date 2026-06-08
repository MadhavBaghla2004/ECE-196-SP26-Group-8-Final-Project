---
layout: home_with_sidebar
title: ECE 196 Group 8 Final Project
permalink: /
---

<!-- ═══════════════════════════════ HOME ═══════════════════════════════ -->
<div class="content-glass" id="home" style="text-align:center; max-width:820px; margin:0 auto;">

  <style>
    .home-slideshow {
      position: relative;
      width: 440px;
      height: 300px;
      max-width: 100%;
      margin: 0 auto 22px;
      border-radius: 14px;
      overflow: hidden;
      box-shadow: 0 8px 30px rgba(0,0,0,0.7);
      border: 1px solid rgba(255,255,255,0.15);
    }

    .home-slide {
      position: absolute;
      inset: 0;
      opacity: 0;
      animation: homeFade 12s infinite;
    }

    .home-slide:nth-child(1) {
      animation-delay: 0s;
    }

    .home-slide:nth-child(2) {
      animation-delay: 6s;
    }

    .home-slide video,
    .home-slide img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }

    @keyframes homeFade {
      0% { opacity: 0; }
      8% { opacity: 1; }
      42% { opacity: 1; }
      50% { opacity: 0; }
      100% { opacity: 0; }
    }
  </style>

  <div class="home-slideshow">

    <!-- Slide 1: Video -->
    <div class="home-slide">
      <video autoplay muted loop playsinline>
        <source src="{{ '/images/Autogreen Homepage.mp4' | relative_url }}" type="video/mp4">
      </video>
    </div>

    <!-- Slide 2: Image -->
    <div class="home-slide">
      <img src="{{ '/images/PrototypePreview.png' | relative_url }}" alt="Home Hydroponic System">
    </div>

  </div>

  <p style="color:#ffffff; font-size:1.7rem; font-weight:800; letter-spacing:0.3px; margin:0 0 6px; text-shadow:0 2px 8px rgba(0,0,0,0.6);">
    ECE 196 SP26 Group 8 Final Project
  </p>

  <h2 style="color:#ffffff; font-size:1.7rem; font-weight:800; margin:0 0 14px; line-height:1.3; text-shadow:0 2px 8px rgba(0,0,0,0.6);">
    AutoGreen: Automated Greenhouse
  </h2>

  <p style="color:rgba(255,255,255,0.72); font-size:1rem; line-height:1.6; margin:0 0 24px;">
    An affordable, sensor-driven growing system that automates seed germination so anyone can grow fresh produce at the comfort of their home
  </p>

</div>

<!-- ═══════════════════════════════ TEAM ════════════════════════════════ -->
<div class="content-glass" id="team" style="text-align:center; max-width:820px; margin:0 auto;">
  <h2 style="color:#ffffff; font-size:1.7rem; font-weight:800; margin:0 0 28px; text-shadow:0 2px 8px rgba(0,0,0,0.6);">Our Team</h2>
  <div style="display:flex; justify-content:center; gap:24px; flex-wrap:nowrap;">

    <div style="text-align:center; width:180px; flex-shrink:0;">
      <img src="{{ '/images/stephen.jpg' | relative_url }}" alt="Stephen"
           style="width:150px; height:150px; object-fit:cover; border-radius:12px; box-shadow:0 6px 20px rgba(0,0,0,0.6); border:2px solid rgba(255,255,255,0.2);">
      <h3 style="margin:10px 0 3px; font-weight:800; color:#ffffff; font-size:1rem;">Stephen Huang</h3>
      <p style="margin:0 0 10px; font-size:0.83rem; color:rgba(255,255,255,0.65);">4th Year, Computer Engineering</p>
      <div style="display:flex; justify-content:center; gap:10px;">
        <a href="https://github.com/bordium" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" style="width:24px; filter:invert(1) opacity(0.8);"></a>
        <a href="https://www.linkedin.com/in/stephenhuangg/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" style="width:24px; opacity:0.9;"></a>
      </div>
    </div>

    <div style="text-align:center; width:180px; flex-shrink:0;">
      <img src="{{ '/images/Madhav.jpeg' | relative_url }}" alt="Madhav"
           style="width:150px; height:150px; object-fit:cover; border-radius:12px; box-shadow:0 6px 20px rgba(0,0,0,0.6); border:2px solid rgba(255,255,255,0.2);">
      <h3 style="margin:10px 0 3px; font-weight:800; color:#ffffff; font-size:1rem;">Madhav Baghla</h3>
      <p style="margin:0 0 10px; font-size:0.83rem; color:rgba(255,255,255,0.65);">4th Year, Computer Engineering</p>
      <div style="display:flex; justify-content:center; gap:10px;">
        <a href="https://github.com/MadhavBaghla2004" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" style="width:24px; filter:invert(1) opacity(0.8);"></a>
        <a href="https://www.linkedin.com/in/madhavbaghla/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" style="width:24px; opacity:0.9;"></a>
      </div>
    </div>

    <div style="text-align:center; width:180px; flex-shrink:0;">
      <img src="{{ '/images/Nathaniel.jpg' | relative_url }}" alt="Nathaniel"
           style="width:150px; height:150px; object-fit:cover; border-radius:12px; box-shadow:0 6px 20px rgba(0,0,0,0.6); border:2px solid rgba(255,255,255,0.2);">
      <h3 style="margin:10px 0 3px; font-weight:800; color:#ffffff; font-size:1rem;">Nathaniel Miller</h3>
      <p style="margin:0 0 10px; font-size:0.83rem; color:rgba(255,255,255,0.65);">4th Year, Electrical Engineering</p>
      <div style="display:flex; justify-content:center; gap:10px;">
        <a href="https://github.com/Nathan-Miller" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" style="width:24px; filter:invert(1) opacity(0.8);"></a>
        <a href="https://www.linkedin.com/in/ncmiller98/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" style="width:24px; opacity:0.9;"></a>
      </div>
    </div>

  </div>
</div>
<!-- ══════════════════════════════ PROBLEM ═══════════════════════════════ -->
<div class="content-glass" id="problem" style="max-width:820px; margin:0 auto;">

  <h2 style="color:#ffffff; font-size:1.7rem; font-weight:800; text-align:center; margin:0 0 24px; text-shadow:0 2px 8px rgba(0,0,0,0.6);">
    The Problem
  </h2>

 <!-- Top Image -->
<div style="text-align:center; margin-bottom:28px;">
  <img src="{{ '/images/HydroponicsFailure.jpg' | relative_url }}" alt="Hydroponics Failure Story"
       style="width:100%;
       max-width:300px;
       aspect-ratio:1/1;
       object-fit:cover;
       border-radius:16px;
       border:1px solid rgba(255,255,255,0.12);
       box-shadow:0 6px 20px rgba(0,0,0,0.6);">
</div>

<!-- Problem Definition -->
<h3 style="color:#a8e6a3; font-size:1.15rem; font-weight:700; margin:0 0 18px;">
  Problem Definition
</h3>

<div style="display:flex; flex-direction:column; gap:14px; margin-bottom:36px;">

  <div style="display:flex; align-items:flex-start; gap:14px; background:rgba(30,80,30,0.45); border:1px solid rgba(120,220,120,0.25); border-radius:12px; padding:16px;">
    <div style="font-size:1.4rem;">💰</div>
    <div style="color:rgba(255,255,255,0.88); line-height:1.7;">
      Beginners have to invest lots of time and money to start in hydroponics.
    </div>
  </div>

  <div style="display:flex; align-items:flex-start; gap:14px; background:rgba(30,80,30,0.45); border:1px solid rgba(120,220,120,0.25); border-radius:12px; padding:16px;">
    <div style="font-size:1.4rem;">🌱</div>
    <div style="color:rgba(255,255,255,0.88); line-height:1.7;">
      Beginners have low success with hydroponic seed germination.
    </div>
  </div>

  <div style="display:flex; align-items:flex-start; gap:14px; background:rgba(30,80,30,0.45); border:1px solid rgba(120,220,120,0.25); border-radius:12px; padding:16px;">
    <div style="font-size:1.4rem;">🌡️</div>
    <div style="color:rgba(255,255,255,0.88); line-height:1.7;">
      Maintaining temperature and moisture in soilless mediums is difficult.
    </div>
  </div>

</div>

<!-- Motivation Image -->
<div style="text-align:center; margin-bottom:22px;">
  <img src="{{ '/images/ProblemMotivation.png' | relative_url }}" alt="Motivation Story"
       style="width:100%;
       max-height:420px;
       object-fit:contain;
       border-radius:16px;
       border:1px solid rgba(255,255,255,0.12);
       box-shadow:0 6px 20px rgba(0,0,0,0.6);">
  <p style="font-size:0.8rem; color:rgba(255,255,255,0.55); font-style:italic; margin:8px 0 0;">
    Image created using AI
  </p>
</div>


<!-- Motivation -->
<h3 style="color:#a8e6a3; font-size:1.15rem; font-weight:700; margin:0 0 10px;">
  Motivation
</h3>

<p style="font-size:1.05rem; color:rgba(255,255,255,0.88); line-height:1.8; margin:0;">
  Nathaniel invested significant time and money into a hydroponics system, but the seeds failed to germinate due to environmental conditions, highlighting the challenges beginners face when growing plants hydroponically.
</p>

</div>

<!-- ══════════════════════════════ SOLUTION ═══════════════════════════════ -->
<div class="content-glass" id="solution" style="max-width:820px; margin:0 auto;">

  <h2 style="color:#ffffff; font-size:1.7rem; font-weight:800; text-align:center; margin:0 0 24px; text-shadow:0 2px 8px rgba(0,0,0,0.6);">Our Solution</h2>

  <!-- Existing Solutions -->
  <h3 style="color:#a8e6a3; font-size:1.15rem; font-weight:700; margin:0 0 10px;">Existing Solutions</h3>
  <p style="font-size:1.05rem; color:rgba(255,255,255,0.88); line-height:1.8; margin:0 0 20px;">
   Many hydroponic systems simplify growing but still require users to manage germination conditions and plant-specific requirements, creating a learning curve that can lead to failed growth.
  </p>

<!-- Patent card 1 -->
<div style="background:rgba(8,35,8,0.75); border:1px solid rgba(120,220,120,0.25); border-radius:14px; padding:24px; margin-bottom:16px;">

  <div style="width:100%; max-width:420px; height:220px; margin:0 auto 18px auto; background:#fff; border-radius:10px; border:1px solid rgba(255,255,255,0.1); display:flex; align-items:center; justify-content:center; overflow:hidden;">
    <img src="{{ '/images/Patent1.webp' | relative_url }}" alt="Seed Monitoring System"
         style="max-width:100%; max-height:100%; object-fit:contain; display:block;">
  </div>

  <div style="font-size:0.95rem; font-weight:700; letter-spacing:0.8px; margin-bottom:6px;">
    <a href="https://patents.google.com/patent/US20230089847A1/en"
       target="_blank"
       style="color:#a8e6a3; text-decoration:none;">
      📋 US12543625B2 🔗
    </a>
  </div>

  <div style="font-size:1.15rem; color:#ffffff; font-weight:800; margin-bottom:10px;">
    Systems and apparatuses for soil and seed monitoring
  </div>

  <div style="font-size:1rem; color:rgba(255,255,255,0.8); line-height:1.75;">
    A precision agriculture system that uses sensors and data processing to monitor soil conditions and predict seed germination timing, emergence, and risk.
  </div>

</div>


<!-- Patent card 2 -->
<div style="background:rgba(8,35,8,0.75); border:1px solid rgba(120,220,120,0.25); border-radius:14px; padding:24px; margin-bottom:32px;">

  <div style="width:100%; max-width:420px; height:220px; margin:0 auto 18px auto; background:#fff; border-radius:10px; border:1px solid rgba(255,255,255,0.1); display:flex; align-items:center; justify-content:center; overflow:hidden;">
    <img src="{{ '/images/Patent2.png' | relative_url }}" alt="Seedling Tray Assembly"
         style="max-width:100%; max-height:100%; object-fit:contain; display:block;">
  </div>

  <div style="font-size:0.95rem; font-weight:700; letter-spacing:0.8px; margin-bottom:6px;">
    <a href="https://patents.google.com/patent/US4236350A/en"
       target="_blank"
       style="color:#a8e6a3; text-decoration:none;">
      📋 US4236350A 🔗
    </a>
  </div>

  <div style="font-size:1.15rem; color:#ffffff; font-weight:800; margin-bottom:10px;">
    Seedling tray assembly and greenhouse
  </div>

  <div style="font-size:1rem; color:rgba(255,255,255,0.8); line-height:1.75;">
    A modular seedling tray and greenhouse assembly designed to efficiently grow and manage plant seedlings in controlled environments.
  </div>

</div>

<!-- Proposed Solution -->
<h3 style="color:#a8e6a3; font-size:1.15rem; font-weight:700; margin:0 0 16px;">
  Proposed Solution
</h3>

<!-- First Image -->
<div style="text-align:center; margin-bottom:24px;">
  <img src="{{ '/images/homehydroponicsystem.png' | relative_url }}" 
       alt="Home Hydroponic System"
       style="width:75%; max-width:520px; height:auto;
       border-radius:12px;
       box-shadow:0 6px 24px rgba(0,0,0,0.6);
       border:1px solid rgba(255,255,255,0.12);">
</div>

<!-- What It Does -->
<div style="background:rgba(8,35,8,0.75);
            border:1px solid rgba(120,220,120,0.25);
            border-radius:14px;
            padding:24px;
            margin-bottom:28px;">

  <div style="font-size:0.82rem;
              color:#a8e6a3;
              text-transform:uppercase;
              letter-spacing:1px;
              font-weight:700;
              margin-bottom:14px;">
    🎯 What It Does
  </div>

  <ul style="margin:0;
             padding-left:20px;
             color:rgba(255,255,255,0.88);
             font-size:1rem;
             line-height:2;">

    <li>Automatically monitors and adjusts temperature, humidity, water level, and nutrient concentrations</li>

    <li>Provides real-time feedback and notifications via a smartphone app</li>

    <li>Recommends optimal settings based on selected seed species from a cloud database</li>

    <li>Enables manual adjustments and social sharing of plant growth progress</li>
  </ul>
</div>

<!-- Second Image -->
<div style="text-align:center; margin-bottom:24px;">
  <img src="{{ '/images/hydroponicsystemdiag.png' | relative_url }}" 
       alt="Hydroponic System Diagram"
       style="width:75%; max-width:520px; height:auto;
       border-radius:12px;
       box-shadow:0 6px 24px rgba(0,0,0,0.6);
       border:1px solid rgba(255,255,255,0.12);">
</div>

<!-- Technology -->
<div style="background:rgba(8,35,8,0.75);
            border:1px solid rgba(120,220,120,0.25);
            border-radius:14px;
            padding:24px;
            margin-bottom:24px;">

  <div style="font-size:0.82rem;
              color:#a8e6a3;
              text-transform:uppercase;
              letter-spacing:1px;
              font-weight:700;
              margin-bottom:14px;">
    ⚙️ Technology
  </div>

  <ul style="margin:0;
             padding-left:20px;
             color:rgba(255,255,255,0.88);
             font-size:1rem;
             line-height:2;">

    <li>Microcontroller with sensor array (temperature, humidity, pH, water level, nutrients)</li>

    <li>PID control loops for precise environmental regulation</li>

    <li>Mobile app for species selection, live monitoring, and remote control</li>

    <li>Cloud database with community-sourced plant data and regional recommendations</li>
  </ul>
</div>

<!-- System Overview -->
<h3 style="color:#a8e6a3; font-size:1.15rem; font-weight:700; margin:0 0 16px;">
  System Overview
</h3>

<div style="text-align:center; margin-bottom:40px;">
  <img src="{{ '/images/SystemBlockDiag.png' | relative_url }}"
       alt="System Overview"
       style="width:75%; max-width:700px; height:auto;
       border-radius:12px;
       box-shadow:0 6px 24px rgba(0,0,0,0.6);
       border:1px solid rgba(255,255,255,0.12);">
</div>

<!-- Software & Hardware Overview -->
<div style="display:flex;
            gap:24px;
            justify-content:center;
            align-items:flex-start;
            flex-wrap:wrap;
            margin-bottom:32px;">

  <!-- Software Overview -->
  <div style="flex:1; min-width:280px; max-width:380px;">

    <h3 style="color:#a8e6a3;
               font-size:1.1rem;
               font-weight:700;
               margin:0 0 12px;
               text-align:center;">
      Software Overview
    </h3>

    <img src="{{ '/images/SoftwareBlockDiag.png' | relative_url }}"
         alt="Software Overview"
         style="width:100%;
         height:auto;
         border-radius:12px;
         box-shadow:0 6px 24px rgba(0,0,0,0.6);
         border:1px solid rgba(255,255,255,0.12);">

  </div>

  <!-- Hardware Overview -->
  <div style="flex:1; min-width:280px; max-width:380px;">

    <h3 style="color:#a8e6a3;
               font-size:1.1rem;
               font-weight:700;
               margin:0 0 12px;
               text-align:center;">
      Hardware Overview
    </h3>

    <img src="{{ '/images/HardwareBlockDiag.png' | relative_url }}"
         alt="Hardware Overview"
         style="width:100%;
         height:auto;
         border-radius:12px;
         box-shadow:0 6px 24px rgba(0,0,0,0.6);
         border:1px solid rgba(255,255,255,0.12);">

  </div>

</div>

</div>

<!-- ══════════════════════════════ PCB ═══════════════════════════════ -->
<div class="content-glass" id="pcb" style="max-width:820px; margin:0 auto;">

  <h2 style="color:#ffffff;
             font-size:1.7rem;
             font-weight:800;
             text-align:center;
             margin:0 0 24px;
             text-shadow:0 2px 8px rgba(0,0,0,0.6);">
    PCB Design
  </h2>

  <div style="display:flex; flex-direction:column; gap:40px;">

    <!-- PCB Layout -->
    <div style="text-align:left; width:100%;">

      <p style="font-size:1.1rem;
                color:rgba(255,255,255,0.75);
                margin:0 0 14px;">
        PCB Layout
      </p>

      <div style="display:flex; justify-content:center;">

        <img src="{{ '/images/PCBLayout.png' | relative_url }}"
             alt="PCB Layout"

             style="width:420px;
             height:300px;
             object-fit:contain;
             display:block;

             border-radius:12px;
             box-shadow:0 6px 24px rgba(0,0,0,0.6);
             border:1px solid rgba(255,255,255,0.12);">

      </div>
    </div>

    <!-- Board Front Layout -->
    <div style="text-align:left; width:100%;">

      <p style="font-size:1.1rem;
                color:rgba(255,255,255,0.75);
                margin:0 0 14px;">
        Board Front Layout
      </p>

      <div style="display:flex;
                  flex-wrap:wrap;
                  justify-content:center;
                  align-items:center;
                  gap:20px;">

        <img src="{{ '/images/PCBFront.png' | relative_url }}"
             alt="Board Front Layout"

             style="width:360px;
             height:300px;
             object-fit:contain;
             display:block;

             border-radius:12px;
             box-shadow:0 6px 24px rgba(0,0,0,0.6);
             border:1px solid rgba(255,255,255,0.12);">

        <img src="{{ '/images/PCBTopLayoutUA.png' | relative_url }}"
             alt="Board Front Layout 2"

             style="width:360px;
             height:300px;
             object-fit:contain;
             display:block;

             border-radius:12px;
             box-shadow:0 6px 24px rgba(0,0,0,0.6);
             border:1px solid rgba(255,255,255,0.12);">

      </div>
    </div>

    <!-- Board Back Layout -->
    <div style="text-align:left; width:100%;">

      <p style="font-size:1.1rem;
                color:rgba(255,255,255,0.75);
                margin:0 0 14px;">
        Board Back Layout
      </p>

      <div style="display:flex;
                  flex-wrap:wrap;
                  justify-content:center;
                  align-items:center;
                  gap:20px;">

        <img src="{{ '/images/PCBBack.png' | relative_url }}"
             alt="Board Back Layout"

             style="width:360px;
             height:300px;
             object-fit:contain;
             display:block;

             border-radius:12px;
             box-shadow:0 6px 24px rgba(0,0,0,0.6);
             border:1px solid rgba(255,255,255,0.12);">

        <img src="{{ '/images/PCBBottomLayoutUA.jpg' | relative_url }}"
             alt="Board Back Layout 2"

             style="width:360px;
             height:300px;
             object-fit:contain;
             display:block;

             border-radius:12px;
             box-shadow:0 6px 24px rgba(0,0,0,0.6);
             border:1px solid rgba(255,255,255,0.12);">

      </div>
    </div>

    <!-- PCB Top 3D View -->
    <div style="text-align:left; width:100%;">

      <p style="font-size:1.1rem;
                color:rgba(255,255,255,0.75);
                margin:0 0 14px;">
        PCB Top 3D View
      </p>

      <div style="display:flex;
                  flex-wrap:wrap;
                  justify-content:center;
                  align-items:center;
                  gap:20px;">

        <img src="{{ '/images/PCBTopAnnotated.png' | relative_url }}"
             alt="PCB 3D Top"

             style="width:360px;
             height:300px;
             object-fit:contain;
             display:block;

             border-radius:12px;
             box-shadow:0 6px 24px rgba(0,0,0,0.6);
             border:1px solid rgba(255,255,255,0.12);">

        <img src="{{ '/images/PCBTopView.jpg' | relative_url }}"
             alt="PCB 3D Top 2"

             style="width:360px;
             height:300px;
             object-fit:contain;
             display:block;

             border-radius:12px;
             box-shadow:0 6px 24px rgba(0,0,0,0.6);
             border:1px solid rgba(255,255,255,0.12);">

      </div>
    </div>

    <!-- PCB Bottom 3D View -->
    <div style="text-align:left; width:100%;">

      <p style="font-size:1.1rem;
                color:rgba(255,255,255,0.75);
                margin:0 0 14px;">
        PCB Bottom 3D View
      </p>

      <div style="display:flex;
                  flex-wrap:wrap;
                  justify-content:center;
                  align-items:center;
                  gap:20px;">

        <img src="{{ '/images/PCBBottomAnnotated.png' | relative_url }}"
             alt="PCB 3D Bottom"

             style="width:360px;
             height:300px;
             object-fit:contain;
             display:block;

             border-radius:12px;
             box-shadow:0 6px 24px rgba(0,0,0,0.6);
             border:1px solid rgba(255,255,255,0.12);">

        <img src="{{ '/images/PCBBackView.jpg' | relative_url }}"
             alt="PCB 3D Bottom 2"

             style="width:360px;
             height:300px;
             object-fit:contain;
             display:block;

             border-radius:12px;
             box-shadow:0 6px 24px rgba(0,0,0,0.6);
             border:1px solid rgba(255,255,255,0.12);">

      </div>
    </div>

  </div>

  <!-- PCB Functionality -->
  <h3 style="color:#ffffff;
             font-size:1.4rem;
             font-weight:700;
             margin:40px 0 10px;">
    PCB Functionality
  </h3>

  <p style="font-size:1.05rem;
            color:rgba(255,255,255,0.8);
            line-height:1.7;
            text-align:justify;
            margin:0;">

    The purpose of our PCB is to serve as the central control system for the smart hydroponics setup by integrating power management, sensing, and actuation into a single platform. It performs power conversions by taking a 12V input and stepping it down to regulated 5V and 3.3V levels required by different components. The board also provides structured I/O connections for sensors such as moisture, temperature, and water level, enabling the ESP32 to collect environmental data. Additionally, it handles peripheral device control by using switching components to operate actuators like pumps, fans, heaters, and LEDs based on sensor inputs, allowing the system to automatically maintain optimal growing conditions.

  </p>

</div>

<!-- ═══════════════════════════════ PROTOTYPE ═══════════════════════════════ -->
<div class="content-glass" id="prototype" style="max-width:820px; margin:0 auto;">

  <h2 style="color:#ffffff; font-size:1.7rem; font-weight:800; text-align:center; margin:0 0 24px; text-shadow:0 2px 8px rgba(0,0,0,0.6);">
    Prototypes
  </h2>

  <!-- Prototype 1 -->
  <div style="display:flex; gap:24px; align-items:center; background:rgba(8,35,8,0.75); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:22px; margin-bottom:24px; flex-wrap:wrap;">

    <!-- Image -->
    <div style="flex:1; min-width:280px; text-align:center;">
      <img src="{{ '/images/EnclosureAssembledView.png' | relative_url }}" alt="Enclosure - Assembled View"
           style="width:100%; max-width:360px; height:auto; border-radius:14px; border:1px solid rgba(255,255,255,0.12); box-shadow:0 6px 24px rgba(0,0,0,0.6);">

      <div style="color:#a8e6a3; font-size:0.9rem; font-weight:700; margin-top:10px;">
        Enclosure - Assembled View
      </div>
    </div>

    <!-- Text -->
    <div style="flex:1; min-width:260px; text-align:left;">
      <h3 style="color:#ffffff; font-size:1.15rem; font-weight:800; margin:0 0 16px;">
        Features
      </h3>

      <div style="display:flex; flex-direction:column; gap:12px;">

        <div style="display:flex; align-items:center; gap:12px; color:rgba(255,255,255,0.86);">
          <span style="font-size:1.3rem;">🛒</span>
          <span>Off Shelf Components</span>
        </div>

        <div style="display:flex; align-items:center; gap:12px; color:rgba(255,255,255,0.86);">
          <span style="font-size:1.3rem;">🌱</span>
          <span>Seed Cell Tray</span>
        </div>

        <div style="display:flex; align-items:center; gap:12px; color:rgba(255,255,255,0.86);">
          <span style="font-size:1.3rem;">💧</span>
          <span>Water Reservoir</span>
        </div>

      </div>
    </div>

  </div>

  <!-- Prototype 2 -->
  <div style="display:flex; gap:24px; align-items:center; background:rgba(8,35,8,0.75); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:22px; margin-bottom:24px; flex-wrap:wrap;">

    <!-- Image -->
    <div style="flex:1; min-width:280px; text-align:center;">
      <img src="{{ '/images/EnclosureExplodedView.png' | relative_url }}" alt="Enclosure - Exploded View"
           style="width:100%; max-width:360px; height:auto; border-radius:14px; border:1px solid rgba(255,255,255,0.12); box-shadow:0 6px 24px rgba(0,0,0,0.6);">

      <div style="color:#a8e6a3; font-size:0.9rem; font-weight:700; margin-top:10px;">
        Enclosure - Exploded View
      </div>
    </div>

    <!-- Text -->
    <div style="flex:1; min-width:260px; text-align:left;">
      <h3 style="color:#ffffff; font-size:1.15rem; font-weight:800; margin:0 0 16px;">
        Features
      </h3>

      <div style="display:flex; flex-direction:column; gap:12px;">

        <div style="display:flex; align-items:center; gap:12px; color:rgba(255,255,255,0.86);">
          <span style="font-size:1.3rem;">💦</span>
          <span>Attached Water Tray</span>
        </div>

        <div style="display:flex; align-items:center; gap:12px; color:rgba(255,255,255,0.86);">
          <span style="font-size:1.3rem;">🧠</span>
          <span>Isolated Electronics Bay</span>
        </div>

        <div style="display:flex; align-items:center; gap:12px; color:rgba(255,255,255,0.86);">
          <span style="font-size:1.3rem;">📦</span>
          <span>Cell Tray Spacer</span>
        </div>

      </div>
    </div>

  </div>

  <!-- Prototype 3 -->
  <div style="display:flex; gap:24px; align-items:center; background:rgba(8,35,8,0.75); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:22px; margin-bottom:24px; flex-wrap:wrap;">

    <!-- Image -->
    <div style="flex:1; min-width:280px; text-align:center;">
      <img src="{{ '/images/EnclosureLid.png' | relative_url }}" alt="Enclosure Lid"
           style="width:100%; max-width:360px; height:auto; border-radius:14px; border:1px solid rgba(255,255,255,0.12); box-shadow:0 6px 24px rgba(0,0,0,0.6);">

      <div style="color:#a8e6a3; font-size:0.9rem; font-weight:700; margin-top:10px;">
        Enclosure Lid
      </div>
    </div>

    <!-- Text -->
    <div style="flex:1; min-width:260px; text-align:left;">
      <h3 style="color:#ffffff; font-size:1.15rem; font-weight:800; margin:0 0 16px;">
        Features
      </h3>

      <div style="display:flex; flex-direction:column; gap:12px;">

        <div style="display:flex; align-items:center; gap:12px; color:rgba(255,255,255,0.86);">
          <span style="font-size:1.3rem;">🖨️</span>
          <span>3D Printed Frame</span>
        </div>

        <div style="display:flex; align-items:center; gap:12px; color:rgba(255,255,255,0.86);">
          <span style="font-size:1.3rem;">🪟</span>
          <span>Laser Cut Acrylic Panels</span>
        </div>

        <div style="display:flex; align-items:center; gap:12px; color:rgba(255,255,255,0.86);">
          <span style="font-size:1.3rem;">💡</span>
          <span>LED Strips</span>
        </div>

      </div>
    </div>

  </div>

</div>

<!-- ═══════════════════════════════ SOFTWARE ═══════════════════════════════ -->
<div class="content-glass" id="software" style="max-width:820px; margin:0 auto;">

  <h2 style="color:#ffffff;
             font-size:1.7rem;
             font-weight:800;
             text-align:center;
             margin:0 0 24px;
             text-shadow:0 2px 8px rgba(0,0,0,0.6);">
    Software Architecture
  </h2>

  <p style="font-size:1.05rem;
            color:rgba(255,255,255,0.88);
            line-height:1.8;
            margin:0 0 28px;">
    AutoGreen uses MQTT to enable real-time communication between the mobile application and ESP32 controller. Users can select a plant from the database, automatically configure environmental targets, and monitor sensor readings through the app.
  </p>

  <div style="background:rgba(8,35,8,0.75);
              border:1px solid rgba(120,220,120,0.25);
              border-radius:16px;
              padding:24px;">

    <h3 style="color:#ffffff;
               font-size:1.15rem;
               font-weight:800;
               margin:0 0 18px;">
      Key Features
    </h3>

    <div style="display:flex;
                flex-direction:column;
                gap:14px;">

      <div style="display:flex; align-items:center; gap:12px;">
        <span class="material-icons" style="color:#a8e6a3;">wifi</span>
        <span style="color:rgba(255,255,255,0.86);">
          MQTT-based communication between the mobile application and ESP32
        </span>
      </div>

      <div style="display:flex; align-items:center; gap:12px;">
        <span class="material-icons" style="color:#a8e6a3;">search</span>
        <span style="color:rgba(255,255,255,0.86);">
          Search and select plants from the database
        </span>
      </div>

      <div style="display:flex; align-items:center; gap:12px;">
        <span class="material-icons" style="color:#a8e6a3;">tune</span>
        <span style="color:rgba(255,255,255,0.86);">
          Automatically configure plant-specific environmental targets
        </span>
      </div>

      <div style="display:flex; align-items:center; gap:12px;">
        <span class="material-icons" style="color:#a8e6a3;">monitoring</span>
        <span style="color:rgba(255,255,255,0.86);">
          Live monitoring of temperature, humidity, water temperature, and soil moisture
        </span>
      </div>

      <div style="display:flex; align-items:center; gap:12px;">
        <span class="material-icons" style="color:#a8e6a3;">smart_toy</span>
        <span style="color:rgba(255,255,255,0.86);">
          Automatic control of pumps, fans, heaters, and LED lighting
        </span>
      </div>

      <div style="display:flex; align-items:center; gap:12px;">
        <span class="material-icons" style="color:#a8e6a3;">cloud_sync</span>
        <span style="color:rgba(255,255,255,0.86);">
          Real-time synchronization between hardware state and mobile dashboard
        </span>
      </div>

    </div>

  </div>

</div>

<!-- ═══════════════════════════════ VIDEO DEMO ═══════════════════════════════ -->
<div class="content-glass" id="video-demo" style="max-width:820px; margin:0 auto;">

  <h2 style="color:#ffffff; font-size:1.7rem; font-weight:800; text-align:center; margin:0 0 24px; text-shadow:0 2px 8px rgba(0,0,0,0.6);">
    Video Demo
  </h2>

  <div style="text-align:center; margin-bottom:16px;">
    <iframe
      width="100%"
      height="460"
      src="https://www.youtube.com/embed/e8GXDmgkYN8"
      title="AutoGreen Video Demo"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      allowfullscreen
      style="border:1px solid rgba(255,255,255,0.18); border-radius:14px; background:#0a140a;">
    </iframe>
  </div>

</div>

<!-- ═══════════════════════════════ POSTER ═══════════════════════════════ -->
<div class="content-glass" id="poster" style="max-width:820px; margin:0 auto;">

  <h2 style="color:#ffffff; font-size:1.7rem; font-weight:800; text-align:center; margin:0 0 24px; text-shadow:0 2px 8px rgba(0,0,0,0.6);">
    Poster
  </h2>

  <div style="text-align:center; margin-bottom:16px;">
    <iframe
      src="https://docs.google.com/presentation/d/1P1LDY73guXG3NnxYoRm6mlEnYV38SoIO68-8Utp_w2I/embed?start=false&loop=false&delayms=3000"
      style="width:100%; height:680px; border:1px solid rgba(255,255,255,0.18); border-radius:14px; background:#0a140a;"
      allowfullscreen>
    </iframe>
  </div>

  <div style="text-align:center; margin-bottom:32px;">
    <a href="https://docs.google.com/presentation/d/1P1LDY73guXG3NnxYoRm6mlEnYV38SoIO68-8Utp_w2I/view"
       target="_blank"
       rel="noopener noreferrer"
       style="
         display:inline-block;
         padding:10px 20px;
         background:rgba(120,220,120,0.15);
         border:1px solid rgba(120,220,120,0.35);
         border-radius:10px;
         color:#a8e6a3;
         font-weight:700;
         text-decoration:none;
         transition:all 0.2s ease;">
      📄 Open Poster in New Tab ↗
    </a>
  </div>

</div>

<!-- ═══════════════════════════════ PROJECT TUTORIAL ═══════════════════════════════ -->
<div class="content-glass" id="tutorial" style="max-width:820px; margin:0 auto;">

  <h2 style="color:#ffffff; font-size:1.7rem; font-weight:800; text-align:center; margin:0 0 24px; text-shadow:0 2px 8px rgba(0,0,0,0.6);">Mini Project #3 Tutorials</h2>

  <p style="font-size:1.05rem; color:rgba(255,255,255,0.88); line-height:1.8; margin:0 0 24px;">
    Step-by-step guide on how to build and use the Indoor Smart Hydroponics System.
  </p>

  <!-- Tutorial #1: State Machines -->
  <div style="background:rgba(8,35,8,0.75); border:1px solid rgba(120,220,120,0.25); border-radius:14px; padding:24px; margin-bottom:24px;">
    <div style="font-size:0.82rem; color:#a8e6a3; text-transform:uppercase; letter-spacing:1px; font-weight:700; margin-bottom:14px;">📘 Tutorial #1: State Machines</div>
    <p style="font-size:1rem; color:rgba(255,255,255,0.88); line-height:1.8; margin:0 0 16px;">
      This tutorial focuses on state machines. The controller runs a finite state machine (FSM)
      that decides, on every <code>tick()</code>, which actuators should be active based on the
      latest sensor readings and the user's target setpoints. In <strong>AUTO</strong> mode the FSM
      drives pumping, heating, and venting through independent control loops with deadbands and
      cooldowns; in <strong>MANUAL</strong> mode it parks the outputs so the user is in control.
    </p>

    <!-- State machine diagram -->
    <img src="{{ '/images/StateMachineDiagram.svg' | relative_url }}" alt="Greenhouse controller state machine diagram"
         style="width:100%; max-width:760px; display:block; margin:0 auto 20px; background:rgba(0,0,0,0.35); border:1px solid rgba(255,255,255,0.12); border-radius:12px; padding:12px;">

    <p style="font-size:0.85rem; color:rgba(255,255,255,0.6); text-align:center; font-style:italic; margin:0 0 18px;">
      The FSM switches between MANUAL and AUTO; in AUTO, three independent loops control pumping, heating, and venting.
    </p>

    <!-- Expandable source: StateMachine.cpp -->
    <details style="margin-bottom:14px;">
      <summary style="cursor:pointer; color:#a8e6a3; font-weight:700; font-size:0.95rem; padding:10px 0;">▸ View source: StateMachine.cpp</summary>
    <pre style="background:rgba(0,0,0,0.55); border:1px solid rgba(255,255,255,0.12); border-radius:10px; padding:16px; overflow-x:auto; font-size:0.85rem; line-height:1.5; color:#d6f5d6; margin:10px 0 0;"><code>#include "StateMachine.h"
#include "Config.h"

const char* modeName(GhMode m) {
    return (m == GhMode::AUTO) ? "AUTO" : "MANUAL";
}

String actionsLabel(ActionMask m) {
    if (m == 0) return String("IDLE");
    String s;
    if (m &amp; ACT_PUMPING) { if (s.length()) s += "+"; s += "PUMPING"; }
    if (m &amp; ACT_HEATING) { if (s.length()) s += "+"; s += "HEATING"; }
    if (m &amp; ACT_VENTING) { if (s.length()) s += "+"; s += "VENTING"; }
    return s;
}

String actionsShortLabel(ActionMask m) {
    if (m == 0) return String("IDLE");
    String s;
    if (m &amp; ACT_PUMPING) { if (s.length()) s += "+"; s += "PUMP"; }
    if (m &amp; ACT_HEATING) { if (s.length()) s += "+"; s += "HEAT"; }
    if (m &amp; ACT_VENTING) { if (s.length()) s += "+"; s += "VENT"; }
    return s;
}

StateMachine::StateMachine(Actuators&amp; actuators)
: _act(actuators) {
    _targets.airTempC   = DEFAULT_TARGET_AIR_TEMP_C;
    _targets.waterTempC = DEFAULT_TARGET_WATER_TEMP_C;
    _targets.humidity   = DEFAULT_TARGET_HUMIDITY;
    _targets.soilBin    = DEFAULT_TARGET_SOIL_BIN;
}

void StateMachine::setMode(GhMode m) {
    if (m == _mode) return;
    _mode = m;
    Serial.print("[FSM] mode -&gt; ");
    Serial.println(modeName(_mode));

    // Whichever direction we move, park outputs so the new mode starts clean.
    _actions = 0;
    if (_mode == GhMode::MANUAL) {
        _act.pumpOff();
        _act.fanOff();
        _act.heatersOff();
        // LED stays — it's user-controlled in both modes.
    } else {
        _applyOutputs();
    }
}

float StateMachine::_soilTargetPct() const {
    int b = _targets.soilBin;
    if (b &lt; 1) b = 1;
    if (b &gt; 5) b = 5;
    return SOIL_BIN_PCT[b];
}

// ---- per-action control loops ----

void StateMachine::_updatePumping(const SensorReading&amp; r, uint32_t now) {
    bool pumping = (_actions &amp; ACT_PUMPING) != 0;

    if (pumping) {
        // Stop after PUMP_RUN_MS and start a cooldown.
        if (now - _pumpStartedAt &gt;= PUMP_RUN_MS) {
            _actions &amp;= ~ACT_PUMPING;
            _pumpCooldownUntil = now + PUMP_COOLDOWN_MS;
        }
        return;
    }

    if (now &lt; _pumpCooldownUntil) return;
    if (!r.soilOk || isnan(r.soilPct)) return;

    float targetPct = _soilTargetPct();
    if (r.soilPct &lt; (targetPct - SOIL_DEADBAND_PCT)) {
        _actions |= ACT_PUMPING;
        _pumpStartedAt = now;
    }
}

void StateMachine::_updateHeating(const SensorReading&amp; r) {
    if (!r.shtOk) return;
    bool heating = (_actions &amp; ACT_HEATING) != 0;

    bool tooCold     = r.airTempC &lt;= (_targets.airTempC - TEMP_DEADBAND_C);
    bool warmEnough  = r.airTempC &gt;= _targets.airTempC;

    if (!heating &amp;&amp; tooCold)        _actions |= ACT_HEATING;
    else if (heating &amp;&amp; warmEnough) _actions &amp;= ~ACT_HEATING;
}

void StateMachine::_updateVenting(const SensorReading&amp; r) {
    if (!r.shtOk) return;
    bool venting = (_actions &amp; ACT_VENTING) != 0;

    bool tooHot   = r.airTempC    &gt;= (_targets.airTempC + TEMP_DEADBAND_C);
    bool tooHumid = r.airHumidPct &gt;= (_targets.humidity + HUMID_DEADBAND_PCT);
    bool fine     = r.airTempC    &lt;= _targets.airTempC
                 &amp;&amp; r.airHumidPct &lt;= _targets.humidity;

    if (!venting &amp;&amp; (tooHot || tooHumid)) _actions |= ACT_VENTING;
    else if (venting &amp;&amp; fine)             _actions &amp;= ~ACT_VENTING;
}

void StateMachine::_applyOutputs() {
    if (_actions &amp; ACT_PUMPING) _act.pumpOn();    else _act.pumpOff();
    if (_actions &amp; ACT_VENTING) _act.fanOn();     else _act.fanOff();
    if (_actions &amp; ACT_HEATING) _act.heatersOn(); else _act.heatersOff();
}

void StateMachine::tick(const SensorReading&amp; r) {
    if (_mode == GhMode::MANUAL) return;

    ActionMask before = _actions;
    uint32_t   now    = millis();

    _updatePumping(r, now);
    _updateHeating(r);
    _updateVenting(r);

    if (_actions != before) {
        Serial.print("[FSM] actions -&gt; ");
        Serial.println(actionsLabel(_actions));
    }

    _applyOutputs();
}</code></pre>
    </details>

    <!-- Expandable source: StateMachine.h -->
    <details>
      <summary style="cursor:pointer; color:#a8e6a3; font-weight:700; font-size:0.95rem; padding:10px 0;">▸ View header: StateMachine.h</summary>
    <pre style="background:rgba(0,0,0,0.55); border:1px solid rgba(255,255,255,0.12); border-radius:10px; padding:16px; overflow-x:auto; font-size:0.85rem; line-height:1.5; color:#d6f5d6; margin:10px 0 0;"><code>#ifndef GREENHOUSE_STATEMACHINE_H
#define GREENHOUSE_STATEMACHINE_H

#include &lt;Arduino.h&gt;
#include "Sensors.h"
#include "Actuators.h"

// Each action is an independent bit. The controller can have any combination
// of them active at once (e.g. HEATING + VENTING to warm air while exhausting
// humidity). Mask == 0 is IDLE.
enum ActionFlag : uint8_t {
    ACT_PUMPING = 1 &lt;&lt; 0,
    ACT_HEATING = 1 &lt;&lt; 1,
    ACT_VENTING = 1 &lt;&lt; 2,
};
using ActionMask = uint8_t;

enum class GhMode : uint8_t {
    AUTO = 0,
    MANUAL
};

struct Targets {
    float airTempC   = 16.0f;
    float waterTempC = 13.0f;
    float humidity   = 65.0f;
    int   soilBin    = 3;          // 1, 2, or 3
};

const char* modeName(GhMode m);

/** "IDLE" or "PUMPING+HEATING" etc. */
String actionsLabel(ActionMask m);
/** Compact "IDLE" / "PUMP+HEAT+VENT" — fits the 240px LCD. */
String actionsShortLabel(ActionMask m);

class StateMachine {
public:
    StateMachine(Actuators&amp; actuators);

    void tick(const SensorReading&amp; r);

    ActionMask  actions() const { return _actions; }
    String      actionsString() const { return actionsLabel(_actions); }
    GhMode      mode() const { return _mode; }
    const char* modeLabel() const { return modeName(_mode); }
    const Targets&amp; targets() const { return _targets; }

    void setMode(GhMode m);
    void setTargets(const Targets&amp; t) { _targets = t; }
    void patchTarget_airTemp(float v)   { _targets.airTempC   = v; }
    void patchTarget_waterTemp(float v) { _targets.waterTempC = v; }
    void patchTarget_humidity(float v)  { _targets.humidity   = v; }
    void patchTarget_soilBin(int b)     {
        if (b &gt;= 1 &amp;&amp; b &lt;= 5) _targets.soilBin = b;
    }

private:
    Actuators&amp; _act;
    ActionMask _actions          = 0;
    GhMode     _mode             = GhMode::MANUAL;
    Targets    _targets;
    uint32_t   _pumpStartedAt    = 0;
    uint32_t   _pumpCooldownUntil = 0;

    void _updatePumping(const SensorReading&amp; r, uint32_t now);
    void _updateHeating(const SensorReading&amp; r);
    void _updateVenting(const SensorReading&amp; r);
    void _applyOutputs();
    float _soilTargetPct() const;
};

#endif</code></pre>
    </details>
  </div>

<!-- Tutorial #2: MOSFET Switching -->

<div style="background:rgba(8,35,8,0.75); border:1px solid rgba(120,220,120,0.25); border-radius:14px; padding:24px; margin-bottom:24px;">

  <div style="font-size:0.82rem; color:#a8e6a3; text-transform:uppercase; letter-spacing:1px; font-weight:700; margin-bottom:14px;">📘 Tutorial #2: MOSFET Switching and PWM Control</div>

  <p style="font-size:1rem; color:rgba(255,255,255,0.88); line-height:1.8; margin:0 0 18px;">
    This tutorial introduces MOSFETs as electronic switches that allow an ESP32 to control higher-voltage devices such as pumps, fans, heaters, and LED strips. It explains the difference between relays and MOSFETs, how gate pulldown resistors and decoupling components improve reliability, and why logic-level MOSFETs are important in embedded systems. The tutorial also demonstrates how PWM can be used to control device brightness and speed.  [oai_citation:0‡Nathaniel_Miller_ece196_sp26.md](sediment://file_000000006de471fd9992461e72ba5a82)
  </p>

  <div style="text-align:center;">
    <img src="{{ '/images/BOARD.jpg' | relative_url }}"
         alt="MOSFET PCB Example"
         style="max-width:700px; width:100%; height:auto; border-radius:12px;">
    <p style="font-size:0.9rem; color:rgba(255,255,255,0.65); margin-top:10px;">
      Example PCB implementation showing MOSFET switching circuitry, gate pulldown resistors, and supporting components.
    </p>
  </div>

</div>


<!-- Tutorial #3: Plant Environment Classification -->

<div style="background:rgba(8,35,8,0.75); border:1px solid rgba(120,220,120,0.25); border-radius:14px; padding:24px; margin-bottom:24px;">

  <div style="font-size:0.82rem; color:#a8e6a3; text-transform:uppercase; letter-spacing:1px; font-weight:700; margin-bottom:14px;">📙 Tutorial #3: Plant Environment Classification Using an ESP32 and SHT45</div>

  <p style="font-size:1rem; color:rgba(255,255,255,0.88); line-height:1.8; margin:0 0 18px;">
    This tutorial demonstrates how an ESP32 and SHT45 sensor can be used to collect humidity measurements and classify environmental conditions as Dry, Optimal, or Humid. The activity introduces classification, a core machine learning concept from CSE 151A, using simple threshold-based decision logic. Students learn sensor integration, data acquisition, and automated decision-making using real-world environmental data.  [oai_citation:1‡madhav_baghla_ece196_sp26.md](sediment://file_00000000cb0871f8a5ea094752621741)
  </p>

  <div style="text-align:center;">
    <img src="{{ '/images/MP2.png' | relative_url }}"
         alt="ESP32 and SHT45 Setup"
         style="max-width:700px; width:100%; height:auto; border-radius:12px;">
    <p style="font-size:0.9rem; color:rgba(255,255,255,0.65); margin-top:10px;">
      AI-generated representation of the ESP32 and SHT45 sensor setup used for environmental classification.
    </p>
  </div>

  <h4 style="color:#a8e6a3; margin-top:24px; margin-bottom:12px;">Example Classification Code</h4>

  <pre style="background:#111; color:#f5f5f5; padding:16px; border-radius:10px; overflow-x:auto; font-size:0.9rem;"><code>
if (rh < 40) {
  state = "Dry";
}
else if (rh <= 70) {
  state = "Optimal";
}
else {
  state = "Humid";
}
  </code></pre>

  <p style="font-size:0.9rem; color:rgba(255,255,255,0.65); margin-top:10px;">
    Example humidity classification logic. Code adapted from the tutorial implementation.
  </p>

</div>

</div>

<!-- ═══════════════════════════════ RESOURCES ═══════════════════════════════ -->
<div class="content-glass" id="resources" style="max-width:820px; margin:0 auto;">

  <h2 style="color:#ffffff;
             font-size:1.7rem;
             font-weight:800;
             text-align:center;
             margin:0 0 24px;
             text-shadow:0 2px 8px rgba(0,0,0,0.6);">
    Resources
  </h2>

  <p style="font-size:1.05rem;
            color:rgba(255,255,255,0.88);
            line-height:1.8;
            margin:0 0 32px;">
    Key resources, references, tools, and technologies used throughout the development of AutoGreen.
  </p>

  <div style="display:flex; flex-direction:column; gap:18px;">

    <!-- GitHub -->
    <div style="background:rgba(8,35,8,0.75);
                border:1px solid rgba(120,220,120,0.25);
                border-radius:14px;
                padding:22px;">
      <div style="font-size:1.05rem; font-weight:800; color:#ffffff; margin-bottom:8px;">
        💻 GitHub Repository
      </div>
      <div style="color:rgba(255,255,255,0.78); line-height:1.7; margin-bottom:10px;">
        Contains the source code, firmware, mobile application, and project files used to build AutoGreen.
      </div>
      <a href="https://github.com/bordium/Automated-Greenhouse"
         target="_blank"
         style="color:#a8e6a3; font-weight:700;">
         View Repository ↗
      </a>
    </div>

    <!-- Plant Database -->
    <div style="background:rgba(8,35,8,0.75);
                border:1px solid rgba(120,220,120,0.25);
                border-radius:14px;
                padding:22px;">
      <div style="font-size:1.05rem; font-weight:800; color:#ffffff; margin-bottom:8px;">
        🌱 Plant Database
      </div>
      <div style="color:rgba(255,255,255,0.78); line-height:1.7; margin-bottom:10px;">
        Provided germination and environmental requirements used to build the plant recommendation database.
      </div>
      <a href="https://tomclothier.hort.net/page02.html"
         target="_blank"
         style="color:#a8e6a3; font-weight:700;">
         Visit Resource ↗
      </a>
    </div>

    <!-- SHT45 -->
    <div style="background:rgba(8,35,8,0.75);
                border:1px solid rgba(120,220,120,0.25);
                border-radius:14px;
                padding:22px;">
      <div style="font-size:1.05rem; font-weight:800; color:#ffffff; margin-bottom:8px;">
        🌡️ SHT45 Sensor
      </div>
      <div style="color:rgba(255,255,255,0.78); line-height:1.7; margin-bottom:10px;">
        Datasheet and technical specifications for the temperature and humidity sensor used in AutoGreen.
      </div>
      <a href="https://sensirion.com/products/catalog/SHT45"
         target="_blank"
         style="color:#a8e6a3; font-weight:700;">
         View Datasheet ↗
      </a>
    </div>

    <!-- TI Guide -->
    <div style="background:rgba(8,35,8,0.75);
                border:1px solid rgba(120,220,120,0.25);
                border-radius:14px;
                padding:22px;">
      <div style="font-size:1.05rem; font-weight:800; color:#ffffff; margin-bottom:8px;">
        ⚡ TI Buck Converter Design Guide
      </div>
      <div style="color:rgba(255,255,255,0.78); line-height:1.7; margin-bottom:10px;">
        Reference used to design efficient power conversion and voltage regulation circuitry.
      </div>
      <a href="https://www.ti.com/lit/pdf/slva477"
         target="_blank"
         style="color:#a8e6a3; font-weight:700;">
         Open Guide ↗
      </a>
    </div>

    <!-- MQTT -->
    <div style="background:rgba(8,35,8,0.75);
                border:1px solid rgba(120,220,120,0.25);
                border-radius:14px;
                padding:22px;">
      <div style="font-size:1.05rem; font-weight:800; color:#ffffff; margin-bottom:8px;">
        📡 MQTT Protocol
      </div>
      <div style="color:rgba(255,255,255,0.78); line-height:1.7;">
        Enabled lightweight real-time communication between the ESP32 and mobile application.
      </div>
    </div>

    <!-- Tech Stack -->
    <div style="background:rgba(8,35,8,0.75);
                border:1px solid rgba(120,220,120,0.25);
                border-radius:14px;
                padding:22px;">
      <div style="font-size:1.05rem; font-weight:800; color:#ffffff; margin-bottom:8px;">
        🛠️ Development Tools & Technologies
      </div>
      <div style="color:rgba(255,255,255,0.78); line-height:1.7;">
        KiCAD, Onshape, PlatformIO, C++, Python, TypeScript, and JavaScript were used for PCB design, enclosure development, firmware, backend, and application development.
      </div>
    </div>

    <!-- Course Staff -->
    <div style="background:rgba(8,35,8,0.75);
                border:1px solid rgba(120,220,120,0.25);
                border-radius:14px;
                padding:22px;">
      <div style="font-size:1.05rem; font-weight:800; color:#ffffff; margin-bottom:8px;">
        👨‍🏫 Course Staff
      </div>
      <div style="color:rgba(255,255,255,0.78); line-height:1.7;">
        Special thanks to Prof. Morris, Korey, Ming, Juliana, and Ferrari for their guidance, feedback, and support throughout ECE 196.
      </div>
    </div>

  </div>

</div>

<!-- ══════════════════════════════ MILESTONES ═══════════════════════════════ -->
<div class="content-glass" id="milestones" style="max-width:820px; margin:0 auto;">

  <h2 style="color:#ffffff; font-size:1.7rem; font-weight:800; text-align:center; margin:0 0 24px; text-shadow:0 2px 8px rgba(0,0,0,0.6);">
    Milestones
  </h2>

  <div style="position:relative; padding:8px 0 0 0;">

    <!-- Left vertical line -->
    <div style="position:absolute; left:24px; top:34px; bottom:58px; width:3px; background:rgba(168,230,163,0.35); border-radius:10px;"></div>

    <!-- Milestone 1 -->
    <div style="position:relative; display:flex; gap:22px; margin-bottom:28px;">
      <div style="width:50px; height:50px; border-radius:50%; background:rgba(120,220,120,0.15); border:3px solid rgba(168,230,163,0.7); display:flex; align-items:center; justify-content:center; z-index:2; flex-shrink:0;">
        <div style="width:14px; height:14px; border-radius:50%; background:#a8e6a3;"></div>
      </div>

      <div style="flex:1; display:flex; gap:18px; align-items:center; background:rgba(8,35,8,0.85); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:16px;">
        <img src="{{ '/images/Milestone1.jpg' | relative_url }}" alt="Milestone 1" style="width:150px; height:110px; object-fit:cover; border-radius:14px; border:1px solid rgba(255,255,255,0.15);">
        <div>
          <div style="font-size:0.8rem; color:rgba(160,200,255,0.9); font-weight:700; margin-bottom:6px;">April 25</div>
          <div style="font-size:1.05rem; color:#ffffff; font-weight:800; margin-bottom:6px;">Germination requirements defined</div>
          <div style="font-size:0.9rem; color:rgba(255,255,255,0.72); line-height:1.6;">Defined temperature, humidity, moisture, and success metrics for reliable seed germination.</div>
        </div>
      </div>
    </div>

    <!-- Milestone 2 -->
    <div style="position:relative; display:flex; gap:22px; margin-bottom:28px;">
      <div style="width:50px; height:50px; border-radius:50%; background:rgba(120,220,120,0.15); border:3px solid rgba(168,230,163,0.7); display:flex; align-items:center; justify-content:center; z-index:2; flex-shrink:0;">
        <div style="width:14px; height:14px; border-radius:50%; background:#a8e6a3;"></div>
      </div>

      <div style="flex:1; display:flex; gap:18px; align-items:center; background:rgba(8,35,8,0.85); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:16px;">
        <img src="{{ '/images/Milestone2.png' | relative_url }}" alt="Milestone 2" style="width:150px; height:110px; object-fit:cover; border-radius:14px; border:1px solid rgba(255,255,255,0.15);">
        <div>
          <div style="font-size:0.8rem; color:rgba(160,200,255,0.9); font-weight:700; margin-bottom:6px;">May 2</div>
          <div style="font-size:1.05rem; color:#ffffff; font-weight:800; margin-bottom:6px;">Components selected</div>
          <div style="font-size:0.9rem; color:rgba(255,255,255,0.72); line-height:1.6;">Selected sensors, actuators, ESP32, power components, and supporting hardware.</div>
        </div>
      </div>
    </div>

    <!-- Milestone 3 -->
    <div style="position:relative; display:flex; gap:22px; margin-bottom:28px;">
      <div style="width:50px; height:50px; border-radius:50%; background:rgba(120,220,120,0.15); border:3px solid rgba(168,230,163,0.7); display:flex; align-items:center; justify-content:center; z-index:2; flex-shrink:0;">
        <div style="width:14px; height:14px; border-radius:50%; background:#a8e6a3;"></div>
      </div>

      <div style="flex:1; display:flex; gap:18px; align-items:center; background:rgba(8,35,8,0.85); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:16px;">
        <img src="{{ '/images/Milestone3.png' | relative_url }}" alt="Milestone 3" style="width:150px; height:110px; object-fit:cover; border-radius:14px; border:1px solid rgba(255,255,255,0.15);">
        <div>
          <div style="font-size:0.8rem; color:rgba(160,200,255,0.9); font-weight:700; margin-bottom:6px;">May 9</div>
          <div style="font-size:1.05rem; color:#ffffff; font-weight:800; margin-bottom:6px;">Custom PCB designed</div>
          <div style="font-size:0.9rem; color:rgba(255,255,255,0.72); line-height:1.6;">Designed a custom PCB integrating power regulation, sensors, actuators, and ESP32.</div>
        </div>
      </div>
    </div>

    <!-- Milestone 4 -->
    <div style="position:relative; display:flex; gap:22px; margin-bottom:28px;">
      <div style="width:50px; height:50px; border-radius:50%; background:rgba(120,220,120,0.15); border:3px solid rgba(168,230,163,0.7); display:flex; align-items:center; justify-content:center; z-index:2; flex-shrink:0;">
        <div style="width:14px; height:14px; border-radius:50%; background:#a8e6a3;"></div>
      </div>

      <div style="flex:1; display:flex; gap:18px; align-items:center; background:rgba(8,35,8,0.85); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:16px;">
        <img src="{{ '/images/Milestone4.jpg' | relative_url }}" alt="Milestone 4" style="width:150px; height:110px; object-fit:cover; border-radius:14px; border:1px solid rgba(255,255,255,0.15);">
        <div>
          <div style="font-size:0.8rem; color:rgba(160,200,255,0.9); font-weight:700; margin-bottom:6px;">May 20</div>
          <div style="font-size:1.05rem; color:#ffffff; font-weight:800; margin-bottom:6px;">PCB partially assembled</div>
          <div style="font-size:0.9rem; color:rgba(255,255,255,0.72); line-height:1.6;">Assembled PCB with ESP32 connections, sensor ports, and power regulation.</div>
        </div>
      </div>
    </div>

    <!-- Milestone 5 -->
    <div style="position:relative; display:flex; gap:22px; margin-bottom:28px;">
      <div style="width:50px; height:50px; border-radius:50%; background:rgba(120,220,120,0.15); border:3px solid rgba(168,230,163,0.7); display:flex; align-items:center; justify-content:center; z-index:2; flex-shrink:0;">
        <div style="width:14px; height:14px; border-radius:50%; background:#a8e6a3;"></div>
      </div>

      <div style="flex:1; display:flex; gap:18px; align-items:center; background:rgba(8,35,8,0.85); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:16px;">
        <img src="{{ '/images/Milestone5.png' | relative_url }}" alt="Milestone 5" style="width:150px; height:110px; object-fit:cover; border-radius:14px; border:1px solid rgba(255,255,255,0.15);">
        <div>
          <div style="font-size:0.8rem; color:rgba(160,200,255,0.9); font-weight:700; margin-bottom:6px;">May 22</div>
          <div style="font-size:1.05rem; color:#ffffff; font-weight:800; margin-bottom:6px;">Plant database built</div>
          <div style="font-size:0.9rem; color:rgba(255,255,255,0.72); line-height:1.6;">Created a database storing germination conditions for different seed types.</div>
        </div>
      </div>
    </div>

    <!-- Milestone 6 -->
    <div style="position:relative; display:flex; gap:22px; margin-bottom:28px;">
      <div style="width:50px; height:50px; border-radius:50%; background:rgba(120,220,120,0.15); border:3px solid rgba(168,230,163,0.7); display:flex; align-items:center; justify-content:center; z-index:2; flex-shrink:0;">
        <div style="width:14px; height:14px; border-radius:50%; background:#a8e6a3;"></div>
      </div>

      <div style="flex:1; display:flex; gap:18px; align-items:center; background:rgba(8,35,8,0.85); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:16px;">
        <img src="{{ '/images/Milestone6.png' | relative_url }}" alt="Milestone 6" style="width:150px; height:110px; object-fit:cover; border-radius:14px; border:1px solid rgba(255,255,255,0.15);">
        <div>
          <div style="font-size:0.8rem; color:rgba(160,200,255,0.9); font-weight:700; margin-bottom:6px;">May 23</div>
          <div style="font-size:1.05rem; color:#ffffff; font-weight:800; margin-bottom:6px;">Web app connected</div>
          <div style="font-size:0.9rem; color:rgba(255,255,255,0.72); line-height:1.6;">Connected the web application to the plant database for crop-specific information.</div>
        </div>
      </div>
    </div>

    <!-- Milestone 7 -->
    <div style="position:relative; display:flex; gap:22px; margin-bottom:28px;">
      <div style="width:50px; height:50px; border-radius:50%; background:rgba(120,220,120,0.15); border:3px solid rgba(168,230,163,0.7); display:flex; align-items:center; justify-content:center; z-index:2; flex-shrink:0;">
        <div style="width:14px; height:14px; border-radius:50%; background:#a8e6a3;"></div>
      </div>

      <div style="flex:1; display:flex; gap:18px; align-items:center; background:rgba(8,35,8,0.85); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:16px;">
        <img src="{{ '/images/Milestone7.png' | relative_url }}" alt="Milestone 7" style="width:150px; height:110px; object-fit:cover; border-radius:14px; border:1px solid rgba(255,255,255,0.15);">
        <div>
          <div style="font-size:0.8rem; color:rgba(160,200,255,0.9); font-weight:700; margin-bottom:6px;">May 27</div>
          <div style="font-size:1.05rem; color:#ffffff; font-weight:800; margin-bottom:6px;">PCB fully assembled</div>
          <div style="font-size:0.9rem; color:rgba(255,255,255,0.72); line-height:1.6;">Completed PCB assembly by soldering MOSFETs, connectors, and remaining components.</div>
        </div>
      </div>
    </div>

    <!-- Milestone 8 -->
    <div style="position:relative; display:flex; gap:22px; margin-bottom:28px;">
      <div style="width:50px; height:50px; border-radius:50%; background:rgba(120,220,120,0.15); border:3px solid rgba(168,230,163,0.7); display:flex; align-items:center; justify-content:center; z-index:2; flex-shrink:0;">
        <div style="width:14px; height:14px; border-radius:50%; background:#a8e6a3;"></div>
      </div>

      <div style="flex:1; display:flex; gap:18px; align-items:center; background:rgba(8,35,8,0.85); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:16px;">
        <img src="{{ '/images/Milestone8.png' | relative_url }}" alt="Milestone 8" style="width:150px; height:110px; object-fit:cover; border-radius:14px; border:1px solid rgba(255,255,255,0.15);">
        <div>
          <div style="font-size:0.8rem; color:rgba(160,200,255,0.9); font-weight:700; margin-bottom:6px;">May 28</div>
          <div style="font-size:1.05rem; color:#ffffff; font-weight:800; margin-bottom:6px;">Enclosure designed</div>
          <div style="font-size:0.9rem; color:rgba(255,255,255,0.72); line-height:1.6;">Designed a custom enclosure to house and organize all hardware components.</div>
        </div>
      </div>
    </div>

    <!-- Milestone 9 -->
    <div style="position:relative; display:flex; gap:22px; margin-bottom:28px;">
      <div style="width:50px; height:50px; border-radius:50%; background:rgba(120,220,120,0.15); border:3px solid rgba(168,230,163,0.7); display:flex; align-items:center; justify-content:center; z-index:2; flex-shrink:0;">
        <div style="width:14px; height:14px; border-radius:50%; background:#a8e6a3;"></div>
      </div>

      <div style="flex:1; display:flex; gap:18px; align-items:center; background:rgba(8,35,8,0.85); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:16px;">
        <img src="{{ '/images/Milestone9.png' | relative_url }}" alt="Milestone 9" style="width:150px; height:110px; object-fit:cover; border-radius:14px; border:1px solid rgba(255,255,255,0.15);">
        <div>
          <div style="font-size:0.8rem; color:rgba(160,200,255,0.9); font-weight:700; margin-bottom:6px;">May 30</div>
          <div style="font-size:1.05rem; color:#ffffff; font-weight:800; margin-bottom:6px;">Enclosure components printed</div>
          <div style="font-size:0.9rem; color:rgba(255,255,255,0.72); line-height:1.6;">Fabricated all 3D-printed enclosure components for system assembly.</div>
        </div>
      </div>
    </div>

    <!-- Milestone 10 -->
    <div style="position:relative; display:flex; gap:22px; margin-bottom:28px;">
      <div style="width:50px; height:50px; border-radius:50%; background:rgba(120,220,120,0.15); border:3px solid rgba(168,230,163,0.7); display:flex; align-items:center; justify-content:center; z-index:2; flex-shrink:0;">
        <div style="width:14px; height:14px; border-radius:50%; background:#a8e6a3;"></div>
      </div>

      <div style="flex:1; display:flex; gap:18px; align-items:center; background:rgba(8,35,8,0.85); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:16px;">
        <img src="{{ '/images/Milestone10.jpg' | relative_url }}" alt="Milestone 10" style="width:150px; height:110px; object-fit:cover; border-radius:14px; border:1px solid rgba(255,255,255,0.15);">
        <div>
          <div style="font-size:0.8rem; color:rgba(160,200,255,0.9); font-weight:700; margin-bottom:6px;">June 1</div>
          <div style="font-size:1.05rem; color:#ffffff; font-weight:800; margin-bottom:6px;">Complete system assembled</div>
          <div style="font-size:0.9rem; color:rgba(255,255,255,0.72); line-height:1.6;">Integrated the enclosure, PCB, sensors, actuators, and wiring into the final prototype.</div>
        </div>
      </div>
    </div>

    <!-- Milestone 11 -->
    <div style="position:relative; display:flex; gap:22px; margin-bottom:28px;">
      <div style="width:50px; height:50px; border-radius:50%; background:rgba(120,220,120,0.15); border:3px solid rgba(168,230,163,0.7); display:flex; align-items:center; justify-content:center; z-index:2; flex-shrink:0;">
        <div style="width:14px; height:14px; border-radius:50%; background:#a8e6a3;"></div>
      </div>

      <div style="flex:1; display:flex; gap:18px; align-items:center; background:rgba(8,35,8,0.85); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:16px;">
        <img src="{{ '/images/Milestone11.jpg' | relative_url }}" alt="Milestone 11" style="width:150px; height:110px; object-fit:cover; border-radius:14px; border:1px solid rgba(255,255,255,0.15);">
        <div>
          <div style="font-size:0.8rem; color:rgba(160,200,255,0.9); font-weight:700; margin-bottom:6px;">June 1</div>
          <div style="font-size:1.05rem; color:#ffffff; font-weight:800; margin-bottom:6px;">Hardware - software integrated</div>
          <div style="font-size:0.9rem; color:rgba(255,255,255,0.72); line-height:1.6;"> Connected the app, database, and embedded controller. </div>
        </div>
      </div>
    </div>

    <!-- Milestone 12 -->
    <div style="position:relative; display:flex; gap:22px; margin-bottom:0;">
      <div style="width:50px; height:50px; border-radius:50%; background:rgba(120,220,120,0.15); border:3px solid rgba(168,230,163,0.7); display:flex; align-items:center; justify-content:center; z-index:2; flex-shrink:0;">
        <div style="width:14px; height:14px; border-radius:50%; background:#a8e6a3;"></div>
      </div>

      <div style="flex:1; display:flex; gap:18px; align-items:center; background:rgba(8,35,8,0.85); border:1px solid rgba(120,220,120,0.25); border-radius:16px; padding:16px;">
        <img src="{{ '/images/Milestone12.png' | relative_url }}" alt="Milestone 12" style="width:150px; height:110px; object-fit:cover; border-radius:14px; border:1px solid rgba(255,255,255,0.15);">
        <div>
          <div style="font-size:0.8rem; color:rgba(160,200,255,0.9); font-weight:700; margin-bottom:6px;">June 3</div>
          <div style="font-size:1.05rem; color:#ffffff; font-weight:800; margin-bottom:6px;">Testing &amp; validation completed</div>
          <div style="font-size:0.9rem; color:rgba(255,255,255,0.72); line-height:1.6;">Tested sensing, control logic, and system behavior using the final prototype.</div>
        </div>
      </div>
    </div>

  </div>

  <!-- Challenges -->
  <div style="background:rgba(8,35,8,0.85);
              border:1px solid rgba(255,120,120,0.2);
              border-radius:14px;
              padding:22px;
              margin-top:32px;
              margin-bottom:28px;">

    <h3 style="color:#ffb3b3;
               font-size:1.2rem;
               font-weight:800;
               margin:0 0 16px;">
      Challenges
    </h3>

    <ul style="margin:0;
               padding-left:20px;
               color:rgba(255,255,255,0.75);
               line-height:1.8;
               font-size:0.92rem;">
      <li>Finding reliable and compatible components online that met system and budget requirements</li>
      <li>Searching for accurate PCB footprints and symbols during schematic and PCB development</li>
      <li>Balancing component placement and routing while maintaining clean power distribution</li>
      <li>MOSFETs and connectors were missing from the initial PCB design</li>
    </ul>
  </div>

  <!-- Lessons Learned -->
  <div style="background:rgba(8,35,8,0.85);
              border:1px solid rgba(120,220,120,0.25);
              border-radius:14px;
              padding:22px;
              margin-top:28px;">

    <h3 style="color:#a8e6a3;
               font-size:1.2rem;
               font-weight:800;
               margin:0 0 16px;">
      Lessons Learned
    </h3>

    <ul style="margin:0;
               padding-left:20px;
               color:rgba(255,255,255,0.75);
               line-height:1.8;
               font-size:0.92rem;">
      <li>Proper component placement greatly improves routing efficiency and reliability</li>
      <li>Environmental sensors require unique calibration and communication methods</li>
      <li>Careful power management and decoupling improve sensor stability</li>
      <li>Iterative prototyping helps identify integration issues early</li>
    </ul>
  </div>

  <!-- Pivots -->
  <div style="background:rgba(8,35,8,0.85);
              border:1px solid rgba(255,210,120,0.22);
              border-radius:14px;
              padding:22px;
              margin-top:28px;">

    <h3 style="color:#ffd27a;
               font-size:1.2rem;
               font-weight:800;
               margin:0 0 16px;">
      Pivots
    </h3>

    <ul style="margin:0;
               padding-left:20px;
               color:rgba(255,255,255,0.75);
               line-height:1.8;
               font-size:0.92rem;">
      <li>Pushed enclosure 3D printing later to prioritize PCB completion and testing</li>
      <li>Moved software integration alongside enclosure development for parallel progress</li>
      <li>Focused first on sensing and control before refining the physical enclosure</li>
    </ul>
  </div>

</div>