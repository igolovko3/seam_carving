# Seam carving

 Seam carving (a.k.a. liquid rescaling) is an algorithm for content-aware image resizing, developed by Shai Avidan, of Mitsubishi Electric Research Laboratories (MERL), and Ariel Shamir, of the Interdisciplinary Center and MERL ([link to the original paper](https://perso.crans.org/frenoy/matlab2012/seamcarving.pdf)). It functions by establishing a number of seams (paths of least importance) in an image and automatically removes seams to reduce image size or inserts seams to extend it. Seam carving also allows manually defining areas in which pixels may not be modified, and features the ability to remove whole objects from photographs.

![](https://raw.githubusercontent.com/axu2/improved-seam-carving/master/BroadwayTowerSeamCarving.png)

The purpose of the algorithm is image retargeting, which is the problem of displaying images without distortion on media of various sizes (cell phones, projection screens) using document standards, like HTML, that already support dynamic changes in page layout and text but not images.

This repository contains a realisation of seam carving on Python with samples of rescaled images produced by the algorithm.
