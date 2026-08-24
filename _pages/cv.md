---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download the full CV as a PDF]({{ base_path }}/files/Xin_Yao_CV.pdf){: .btn .btn--primary}

Research interests
======
My research lies at the intersection of machine learning, wireless
communication systems, and information theory. I combine theoretical analysis
with algorithm and system design to develop efficient, secure, and adaptive
methods for distributed learning and dynamic network control, and evaluate
them on real-world wireless testbeds that I build from the physical layer up.

Education
======
* **Ph.D., Electrical and Computer Engineering**, University of Florida, 08/2024–present
  * Advisor: Dr. Mingyue Ji
* **Ph.D. studies, Electrical and Computer Engineering**, University of Utah, 08/2021–07/2024
  * Advisor: Dr. Mingyue Ji (moved to the University of Florida with advisor)
* **M.S., Electrical Engineering**, George Washington University, 01/2020–06/2021
* **B.Eng., Electronic Information Engineering**, Tianjin University of Science and Technology (TUST), 09/2015–06/2019

Research experience
======
* **UAV-based wireless communication platform** — assemble customized drones
  with integrated wireless communication payloads; initialize and tune flight
  controllers; design the ground-to-air communication protocol.
* **UnionLabs: AWS-based remote access and sharing of NextG and IoT
  testbeds** — develop and deploy the AWS-hosted web interface; design PHY
  code for heterogeneous hardware (USRP, LoRa) and the unified Union API that
  connects users' algorithms to it through a single-command abstraction
  layer; support collaborators at multiple universities running experiments
  on several testbeds at once.
* **EdgeAI Lab: real-world wireless communication testbed** — implement the
  physical-layer stack in C++ (modulation, demodulation, filtering,
  synchronization, channel encoding/decoding, carrier-frequency/phase-offset
  correction) with Python APIs for scripted over-the-air experiments and
  automated workflows across heterogeneous hardware.
* **Constrained optimization for real-world problems with reinforcement
  learning** — derive Lyapunov-based optimization objectives under real-world
  constraints, design novel RL state representations, and evaluate
  dynamic-control policies in simulation and on the EdgeAI Lab testbed.
* **Network optimization with low-power (LoRa) communication** — jointly
  adapt LoRa PHY parameters and design path discovery and optimization for
  always-live multi-hop communication under interference and hardware
  outages.
* **A-DEFEAT: adaptive error feedback for decentralized learning** — a new
  decentralized learning algorithm with an adaptive error-compensation
  mechanism, key proof technique, and convergence analysis against existing
  algorithms.
* **Information-theoretic secure aggregation with groupwise keys** — studied
  the information-theoretic foundations of secure aggregation for
  distributed learning; implemented and compared the proposed scheme with
  existing algorithms.
* **Master's projects, George Washington University** — age of information
  with energy harvesting in M/G/1/1 and infinite-buffer queueing models
  (Prof. Omur Ozel); encrypted FTP client/server on Linux (Prof. Tian Lan).
* **Undergraduate projects, TUST** — voice-controlled smart-home system
  (STM32 + LD3320), license-plate recognition in MATLAB, Android music
  player, digital counter.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Presentations, posters and demos
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Technical skills
======
* **Programming:** Python, C/C++, Java, JavaScript, MATLAB, Arduino, JSON, XHTML/DHTML
* **Machine learning:** reinforcement learning, federated learning, secure aggregation, distributed and parallel computing, centralized and decentralized learning
* **Wireless & signal processing:** physical-layer implementation (modulation/demodulation, synchronization, filtering, channel encoding/decoding), real-world testbed development, network protocol analysis
* **Embedded & cloud systems:** STM32 microcontrollers, Android SDK (Eclipse/JDK), AWS, Linux
* **Design & productivity tools:** AutoCAD, Siemens NX, Sharp3D, Adobe (Photoshop, Premiere Pro, After Effects, Acrobat), MS Office

Honors & awards
======
* Third-Prize Scholarship, TUST, 2017
* Advanced Individual of Social Work, TUST, 2016
* Excellent League Member, TUST, 2016
