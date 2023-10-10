---
title: "Towards Automated Void Detection for Search and Rescue with 3D Perception"
collection: publications
permalink: /publication/2023-iros-void-detection
excerpt: 'This work presents a novel approach for semi-automated ex-post-facto detection of voids in the rubble pile of the Surfside Structural Collapse at Miami.'
date: 2023-10-15 # Need to change this to the actual date
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2023'
citation: 'A. Bal, A. Gupta, P. Goyal, D. Merrick, R. Murphy and H. Choset, "Towards Automated Void Detection for Search and Rescue with 3D Perception," IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Detroit, USA, 2023' # Need to edit this
---

Aerial imagery collected from the disaster site with uncrewed aerial systems (UASs) provides an broad view of the disaster scene which is helpful locating multiple void regions at once. 3D reconstructions generated from aerial images capture essential information that can be used to identify and characterize void spaces and analyze terrain mobility for robots. While the use of 3D reconstructions is not real time yet, data analyzed through this method can help predict the occurrence, location, appearance and likelihood of voids in future collapses.

In this paper, we present a novel approach for semi-automated ex-post-facto detection of voids in the rubble pile of the Surfside Structural Collapse at Miami. Our pipeline utilizes the COLMAP Structure from Motion (SfM) workflow to reconstruct point clouds representing the dynamic search and rescue scene at different times. We use stacked point clouds to determine regions that have changed over time. These regions are processed for detecting shape and color priors that we associate with void spaces. The layers in the stack helps us assess the internal dimensions of detected voids.

Our method can be applied to similar previous data or data collected in the future to find regions presenting characteristics of void spaces. A collection of such regions could one day help build learning-based predictive systems for such disasters.

Link to the paper: TBA
