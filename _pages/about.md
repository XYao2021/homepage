---
permalink: /
title: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

I am a Ph.D. candidate in Electrical and Computer Engineering at the
[University of Florida](https://www.ece.ufl.edu/), advised by Dr. Mingyue Ji.
I began my Ph.D. at the University of Utah in 2021 and moved to UF with my
advisor in 2024. Before that, I earned an M.S. in Electrical Engineering from
George Washington University and a B.Eng. in Electronic Information
Engineering from Tianjin University of Science and Technology.

My research lies at the intersection of machine learning, wireless
communication systems, and information theory. I combine theoretical
analysis with algorithm and system design to develop efficient, secure, and
adaptive methods for distributed learning and dynamic network control, and
evaluate them on real-world wireless testbeds that I build from the physical
layer up.

Research
======
* **EdgeAI Lab wireless testbed.** I implement the physical layer in C++ —
  modulation, demodulation, filtering, synchronization, channel
  encoding/decoding, and carrier-frequency/phase-offset correction — with
  Python APIs for scripted over-the-air experiments, and run our group's
  learning algorithms on lab-scale and building-scale deployments.
* **UnionLabs: shared remote testbeds.** An AWS-hosted platform for remote
  access and sharing of NextG and IoT testbeds: a unified Union API
  automatically connects users' algorithms to PHY code for USRP and LoRa
  hardware through a single-command abstraction layer, so collaborators at
  different universities can run experiments on multiple testbeds at once.
* **Learning-driven network control.** I derive Lyapunov-based optimization
  objectives under real-world constraints and deploy reinforcement-learning
  control (Q-learning, DDPG, MADDPG) on live hardware — including joint
  per-slot LoRa PHY adaptation with path discovery and optimization for
  always-live multi-hop communication under interference and hardware
  outages.
* **Decentralized learning and secure aggregation.** A-DEFEAT, a
  decentralized learning algorithm with an adaptive error-feedback mechanism
  and convergence analysis, and information-theoretic secure aggregation
  with groupwise keys.
* **UAV wireless platform.** Custom-assembled drones with wireless payloads
  and a ground-to-air communication protocol for airborne experiments.

See [Projects]({{ base_path }}/portfolio/) for details on each direction and
[Publications]({{ base_path }}/publications/) for papers.

News
======
* **2026** — "FORGE-LoRa: Joint per-Slot PHY Adaptation for Multi-Hop LoRa
  Networks" accepted (X. Yao, A. Bhuyan, M. Ji).
* **Jun 2026** — Presented the A-DEFEAT poster at the North American School
  of Information Theory (NASIT) at BYU.
* **2026** — Presented "Experimental Evaluation of Reinforcement Learning
  for Spectrum Sharing on a Real-Time LoRa Testbed" at IEEE DySPAN 2026.
* **Dec 2025** — Demo (OSWireless) and poster (UnionLabs) at the Warren B.
  Nelms Annual IoT Conference, University of Florida.
* **Oct 2025** — Presented our LDPP-MADDPG power-allocation paper at the
  IEEE MILCOM 2025 6GSECC Workshop.
