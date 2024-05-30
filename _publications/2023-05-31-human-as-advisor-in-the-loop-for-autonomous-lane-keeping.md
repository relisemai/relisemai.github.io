---
title: "Human-as-advisor in the loop for autonomous lane-keeping"
collection: publications
permalink: /publication/2023-05-31-human-as-advisor-in-the-loop-for-autonomous-lane-keeping
excerpt: 'This paper presents a human-as-advisor architecture for shared human-machine autonomy in dynamic systems. In the human-as-advisor architecture, the human provides suggested control actions to the autonomous system; the system uses a model of the human controller to ascertain the system’s state as perceived by the human. The system combines this information with additional sensor measurements, yielding an improved state estimate. We apply this architecture to the problem of lane-centering an autonomous vehicle in the presence of conflicting lane markings that render the true lane center uncertain. '
date: 2023-05-31
venue: 'American Controls Conference'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10156374'
citation: 'R. Mai, S. Mishra, and A. Julius. (2023). &quot;Human-as-advisor in the loop for autonomous lane-keeping.&quot; <i>2023 American Control Conference (ACC)</i>. IEEE, May 31, 2023. doi: 10.23919/acc55779.2023.10156374.'
---

This paper presents a human-as-advisor architecture for shared human-machine autonomy in dynamic systems. In the human-as-advisor architecture, the human provides suggested control actions to the autonomous system; the system uses a model of the human controller to ascertain the system’s state as perceived by the human. The system combines this information with additional sensor measurements, yielding an improved state estimate. We apply this architecture to the problem of lane-centering an autonomous vehicle in the presence of conflicting lane markings that render the true lane center uncertain. We model conflicting lane markings with a multi-component Gaussian mixture model. The human-suggested course of action is interpreted as an additional sensor measurement, which a Kalman filter is designed to combine with a speedometer and camera for improving the state estimate. With human input from our human-as-advisor architecture, the vehicle centers itself in the lane; without human input, the vehicle does not center itself. We also demonstrate the human-as-advisor architecture is robust to additive output matrix uncertainty and non-linear perturbations in the human model used to interpret the human-suggested control actions.
