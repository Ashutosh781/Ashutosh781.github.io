---
title: "Void Detection with 3D Perception"
collection: research
permalink: /research/void-detection
excerpt: 'Semi automated void detection pipeline for rubble pile in Search and Rescue operation'
---

Worked on developing a semi-automated void detection pipeline using registered point clouds of rubble pile in a Search and Rescue operation. The void detection pipeline detects cadidate void regions with fewer false positives.

Our method uses images of static structures around the rubble to reconstruct and register point clouds from multiple days using Structure from motion pipeline.

<img title="Void detection pipeline" alt="Void detection pipeline" src="/images/void-detection.png">

Above image shows the void detection setup - 1) The use of UAS images (Seen in a.) for generating a layered 3D reconstruction (Seen in b.) of the collapse scene. 2) Voids annotated by experts (Seen in c.) being identified by our method (Seen in d.)
