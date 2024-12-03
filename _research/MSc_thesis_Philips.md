---
title: "MSc: Collision-free MPC for Image-Guided Therapy Robots"
authors:
    - name: "Saray Bakker"
      url: "https://saraybakker.github.io/"
      superscript: "1"
    - name: "Bram van de Vrande"
      superscript: "2"
    - name: "Elena Torta"
      url: "https://www.tue.nl/en/research/researchers/elena-torta"
      superscript: "1"
affiliations:
    - name: "TU Eindhoven, The Netherlands"
      superscript: "1"
      url: "https://www.tue.nl/en/research/institutes/eindhoven-artificial-intelligence-systems-institute/robotics"
    - name: "Philips Healthcare, The Netherlands"
      superscript: "2"
      url: "https://www.philips.nl/healthcare/e/image-guided-therapy"
date: 2022-09-01
# This is the short project description, displayed in the project's card"
description: "This MSc thesis
presents a novel formulation of a model predictive control framework for autonomous navigation
of large medical manipulators, such as image-guided therapy robots. "
cover_image: /assets/images/papers/mscphilips/MscPhilips.png # Image displayed in the project's card, make it aspect ratio 1x1 (square) for best results, and keep it a reasonable size (like 1-2MB). Can also be a gif
links: # If you have other website for the project, github repos, datasets, etc. put it here. You can also add an icon from https://icons.getbootstrap.com/
    - name: MSc Thesis Summary
      icon: bi-file-earmark-pdf
      url: "https://research.tue.nl/en/studentTheses/collision-free-mpc-for-image-guided-therapy-robots"
    # - name: Code
    #   icon: bi-github
    #   url: "https://github.com/AndreuMatoses/scalable-collision-avoidance-RL"
# gallery_agents:
#   - "/assets/images/research/MscPhilips.png"
---


{% include figure.html src="/assets/images/papers/mscphilips/MscPhilips.png" width="100%" alt="prototype"%}


This work is part of my master's thesis at the TU Eindhoven, the Netherlands.

## Abstract

Large medical manipulators, such as image-guided therapy robots, are increasingly present in
operating rooms. For non-procedural motions, these robots are controlled by the operator using
a joystick. Clinicians would benefit from automating these movements, such as moving it from
a park to a work position. Classical motion planners are too conservative in planning a full
body collision-free trajectory for such large manipulators in a cluttered environment. This thesis
presents a novel formulation of a model predictive control framework for autonomous navigation
of large medical manipulators. Full-body obstacle avoidance is achieved by representing the body
of the robot as a collection of spheres and ensuring the distance between each sphere and the
obstacles remains in the preferred range via relaxed barrier functions. This is combined with an
adaptive virtual target that moves along a path to avoid excessive accelerations as well as deadlock
and livelock scenarios. The control approach is validated both in simulation and on real hardware
of a commercial image-guided therapy robot.

## Related Publications
The MPC controller as designed in this thesis is used in a related publication, as can be found 
<a href="https://arxiv.org/abs/2311.01133">here</a>.
