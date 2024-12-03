---
title: "Multi-Robot Local Motion Planning Using Dynamic Optimization Fabrics"
authors:
    - name: "Saray Bakker*"
    - name: "Luzia Knoedler*"
    - name: "Max Spahn"
    - name: "Wendelin Böhmer"
    - name: "Javier Alonso-Mora"
affiliations:
    - name: "TU Delft, *both authors contributed equally"
date: 2023-12-01
# This is the short project description, displayed in the project's card"
description: "In this paper, we address the problem of real-time motion planning for multiple robotic manipulators that operate in close proximity. We build upon the concept of dynamic fabrics and extend them to multi-robot systems, referred to as Multi-Robot Dynamic Fabrics (MRDF)."
cover_image: /assets/images/papers/multirobotfabrics/video_rf_cv_2robots.gif # Image displayed in the project's card, make it aspect ratio 1x1 (square) for best results, and keep it a reasonable size (like 1-2MB). Can also be a gif
links: # If you have other website for the project, github repos, datasets, etc. put it here. You can also add an icon from https://icons.getbootstrap.com/
    - name: Paper
      icon: bi-file-earmark-pdf
      url: "https://arxiv.org/abs/2310.12816"
    - name: Code
      icon: bi-github
      url: "https://github.com/tud-amr/multi-robot-fabrics"
    - name: Video
      url: "https://www.youtube.com/watch?v=jaJBrSecDcM"

# gallery_experiments:
#   - "/assets/images/papers/canopies/canopies_rome_test_43_short_good.gif"
#   - "/assets/images/papers/canopies/canopies_rome_test_unload.gif"
---

{% include figure.html src="/assets/images/papers/multirobotfabrics/video_rf_cv_2robots.gif" width="100%" alt="prototype"%}

This paper is presented at the IEEE International Symposium on Multi-Robot & Multi-Agent Systems 
<a href="https://sites.bu.edu/mrs2023/">(MRS), 2023.</a>. 

## Abstract
In this paper, we address the problem of real-time motion planning for multiple robotic manipulators that operate in close proximity. We build upon the concept of dynamic fabrics and extend them to multi-robot systems, referred to as Multi-Robot Dynamic Fabrics (MRDF). This geometric method enables a very high planning frequency for high-dimensional systems at the expense of being reactive and prone to deadlocks. To detect and resolve deadlocks, we propose Rollout Fabrics where MRDF are forward simulated in a decentralized manner. We validate the methods in simulated close-proximity pick-and-place scenarios with multiple manipulators, showing high success rates and real-time performance. 