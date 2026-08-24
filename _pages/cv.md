---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download the full CV as a PDF](/files/Xin_Yao_CV.pdf){: .btn .btn--primary}

Education
======
* **Ph.D., Electrical and Computer Engineering**, University of Florida, 2024–present
  * Advisor: Dr. Mingyue Ji · Focus: machine learning and real-world wireless communication systems
* **Ph.D. studies, Electrical and Computer Engineering**, University of Utah, 2021–2024
  * Transferred to the University of Florida with advisor · GPA 3.97/4.00
* **M.S., Electrical Engineering**, George Washington University, 2020–2021
  * Concentration in Communications and Networks
* **B.Eng., Electronic Information Engineering**, Tianjin University of Science and Technology, 2015–2019
  * Rank 19/119

Research experience
======
* **2024–present: Graduate Research Assistant**, University of Florida
  * Real-world wireless testbed: C++ physical-layer stack (modulation, demodulation, filtering, synchronization, channel encoding/decoding) with Python APIs
  * Reinforcement-learning dynamic control deployed on the physical testbed
  * AWS-hosted web UI (Java, JavaScript, JSON) for remote testbed access
  * UAV platform: drone assembly, flight-controller tuning, wireless payload design
  * Supervisor: Dr. Mingyue Ji

* **2021–2024: Graduate Research Assistant**, University of Utah
  * Decentralized federated-learning algorithm with error compensation
  * Information-theoretic secure aggregation with groupwise keys; Python parallel computing
  * RL-based dynamic control policies for communication systems
  * Supervisor: Dr. Mingyue Ji

* **2020–2021: Graduate Student Researcher**, George Washington University
  * Age of information with energy harvesting in M/G/1/1 and infinite-buffer queueing models
  * Encrypted FTP client/server on Linux, verified with Wireshark
  * Supervisors: Prof. Omur Ozel, Prof. Tian Lan

Skills
======
* **Programming:** Python, C/C++, Java, JavaScript, MATLAB, JSON
* **Machine learning:** reinforcement learning, federated learning, secure aggregation, distributed/parallel computing
* **Wireless & signal processing:** physical-layer implementation, real-world testbed development, Wireshark
* **Embedded & cloud:** STM32 firmware, Android SDK, AWS, Linux

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Honors & awards
======
* Excellent Leader, Sound and Lighting Department, TUST, 2018
* Third-Prize Scholarship, TUST, 2017
* First Prize (group project, orchestral music), Art Performance, TUST, 2016
* Second Prize (personal project, percussion), Art Performance, TUST, 2016
