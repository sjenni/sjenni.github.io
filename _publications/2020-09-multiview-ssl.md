---
title: "Self-Supervised Multi-View Synchronization Learning for 3D Pose Estimation"
collection: publications
permalink: /publication/2020-09-multiview-ssl
date: 2020-09-01
venue: 'Asian Conference on Computer Vision 2020 (oral)'
citation: 'S. Jenni, and P. Favaro. &quot;Self-Supervised Multi-View Synchronization Learning for 3D Pose Estimation.&quot; In <i>ACCV 2020</i>.'
---


[[PDF]](https://arxiv.org/pdf/2010.06218.pdf) [[Project Page]](https://sjenni.github.io/multiview-sync-ssl/) [[Code]](https://github.com/sjenni/multiview-sync-ssl) 

## Abstract

Current state-of-the-art methods cast monocular 3D humanpose  estimation  as  a  learning  problem  by  training  neural  networks  on large  data  sets  of  images  and  corresponding  skeleton  poses.  In  contrast,  we  propose  an  approach  that  can  exploit  small  annotated  datasets by fine-tuning networks pre-trained via self-supervised learning on (large) unlabeled data sets. To drive such networks towards supporting 3D pose estimation during the pre-training step, we introduce a novel self-supervised feature learning task designed to focus on the 3D structure in an image. We exploit images extracted from videos captured with a multi-view camera system. The task is to classify whether two images depict  two  views  of  the  same  scene  up  to  a  rigid  transformation.  In  a multi-view data set, where objects deform in a non-rigid manner, a rigid transformation occurs only between two views taken at the exact same time, i.e., when they are synchronized. We demonstrate the effectiveness of  the  synchronization  task  on  the  Human3.6M  data  set  and  achieve state-of-the-art results in 3D human pose estimation.
