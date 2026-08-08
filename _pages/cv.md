---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Mechanical Engineering, Johns Hopkins University, 2021 - 2025
* M.S.E. in Mechanical Engineering, Johns Hopkins University, 2019 - 2021
* B.S. in Mechanical Engineering, Case Western Reserve University, 2015 - 2019

Work experience
======
* Postdoctoral Associate, Boston University, 2025
  * Supervisor: Dr. Tommaso Ranzani
  * End-to-end learning and policy training framework integrating differentiable simulation with model-based reinforcement learning
  * Optimal state estimation via multi-modal sensor fusion for robust closed-loop control
  * Clinical deployment: GUI implementation, haptic device integration, asynchronous I/O with distributed communication
  * Principal driver of BU's successful ARPA-H AIR proposal — a $30M+ multi-institutional award

* Graduate Research Assistant, Johns Hopkins University, 2021
  * Supervisors: Dr. Iulian Iordachita and Dr. Russell Taylor
  * Flexible needle modeling, simulation, sensing, and autonomous control for percutaneous interventions
  * Finite element simulation, FBG shape sensing, MRI-conditional robot design

Skills
======
* Soft Robot Modeling
  * Piecewise Constant Curvature (PCC) and Constant Curvature (CC) kinematic models
  * Parameter annealing and sensor fusion
* Machine Learning for Robotics
  * LSTM-based learned dynamics with aleatoric/epistemic uncertainty
  * Model-based reinforcement learning (PPO, BPTT, CEM)
  * Data collection, cleaning, and feature engineering
* Sensing and Estimation
  * Camera and EM tracking sensor fusion via Unscented Kalman Filter
  * Pressure-based contact detection
  * Fiber Bragg Grating (FBG) shape sensing
* Robot Control
  * Real-time control systems with ZeroMQ and Protocol Buffers
  * Simulation and hardware deployment pipelines
  * Trapezoidal velocity profiling and constrained random walk sampling
* Computing and Tools
  * HPC cluster computing (SCC/SGE)
  * Python, PyTorch, MATLAB, C/C++
  * Mechanical design, 3D printing, and fabrication

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
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
