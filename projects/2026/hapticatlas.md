---
layout: project
title: "Haptic Atlas: A Wearable System for Non-Visual Navigation Training"
author: Xinyu Jiao and Zhengrui Hao
advisor: Daniel Leithinger and Danil Nagy
year: 2026
links:
  - text: Project Site
    url: https://xinyu-jiao.github.io/haptic-atlas/
---

Haptic Atlas is a wearable navigation training system that delivers directional guidance through touch rather than vision. The system pairs a vibrotactile belt with a handheld controller and a web-based documentation layer, and is designed to support people learning to navigate unfamiliar environments without relying on visual cues. The project addresses a gap between assistive devices, which tend to optimize for moment-to-moment obstacle avoidance, and orientation-and-mobility training, which depends heavily on instructor presence. By encoding direction as patterns of vibration distributed around the body, the belt offers a continuous channel of spatial information that can be practiced, recorded, and refined session by session.

In a typical session, a participant wears the belt while an instructor or remote partner issues directional input through the handheld controller. The belt translates that input into haptic patterns at the corresponding position around the waist, and the website logs the session, captures the walking trace, and stores the result in the archive. The interaction is deliberately split so that the participant's attention stays on the walk while the documentation surface stays on the web, and so that the rhythm of training can be repeated across environments, partners, and difficulty levels without changing the underlying loop.

The system divides responsibilities across three components. The wearable belt handles haptic output and is the only part of the system the participant interacts with during a session. The handheld controller, operated by the instructor or a remote partner, provides real-time directional input and does not depend on the website during the walk itself. The website hosts the project presentation, the session setup forms, the walk trace map, the session results, the iteration archive, and the link to the source repositories. Setup, logging, evidence, and review live on the web; real-time control lives on the hardware.

Sessions are logged with a fixed schema covering level, role, environment, distance, and notes, and the resulting walks are visualized as polylines on a map alongside summary statistics for duration, corrections, and assistance count. The history view groups past sessions and surfaces trace thumbnails so that successive runs can be compared against earlier ones, allowing the belt, the controller's pattern language, and the training scenarios to be read against the data they produced. The archive is built to behave as evidence rather than as a gallery, holding the walks, the corrections, and the contextual notes that together describe what non-visual navigation training looks like in practice.
