---
title: "Enhancing Port Automation: A Novel Object Detection Pipeline for Container Ship Bays"
collection: publications
category: conferences
permalink: /publication/2024-10-01-enhancing-port-automation
date: 2024-10-01
venue: "IEEE Sensors Conference"
authors: "<strong>Junan Lin</strong>, Stefano Marano, Bruno Arsenali, Josip Marjanovic, Niklas Sundholm, Elin Jirskog, Deran Maas*"
paperurl: "https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10784915"
citation: "<strong>Junan Lin</strong>, Stefano Marano, Bruno Arsenali, Josip Marjanovic, Niklas Sundholm, Elin Jirskog, and Deran Maas*. Enhancing Port Automation: A Novel Object Detection Pipeline for Container Ship Bays. <i>IEEE Sensors Conference</i>, 2024."
---

In port automation, efficiency and safety can be significantly increased by autonomous container handling of ship-to-shore cranes. A crucial aspect of achieving this autonomy involves accurately detecting common objects as well as the state of the bay. Previous research has primarily focused on detecting specific types of containers or hatches, which falls short in meeting the demands of complex automated operations. We propose a novel object detection pipeline specifically tailored for this application. In this pipeline the 3D point cloud data is initially transformed into a 2D representation, then fed into the Deformable DETR (Detection Transformer) model to detect objects of interest. Our pipeline successfully detects the positions and sizes of containers, hatch covers, open hatches, and bay areas. Notably, container detection achieves both precision and recall of 0.97. The mean absolute error of the container positions is smaller than 5 cm in all directions. The bay width can be predicted correctly in 99.8 % of the cases. These results are highly promising and pave the way for the automation of ship-to-shore cranes, leading to improved efficiency and enhanced safety.
