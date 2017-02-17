[//]: # (# ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes)

<h3 align="center">
<a href="http://cs.stanford.edu/~adai/publications.html">Angela Dai</a><sup>1</sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://angelxuanchang.github.io">Angel X. Chang</a><sup>2</sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://msavva.github.io">Manolis Savva</a><sup>2</sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="http://www.cs.princeton.edu/~mhalber/">Maciej Halber</a><sup>2</sup><br><a href="http://www.cs.princeton.edu/~funk/">Thomas Funkhouser</a><sup>2</sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="http://graphics.stanford.edu/~niessner/publications.html">Matthias Nie&szlig;ner</a><sup>1</sup>
</h3>

<h4 align="center">
 <sup>1</sup>Stanford University&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<sup>2</sup>Princeton University
</h4>

ScanNet is an RGB-D video dataset containing 2.5 million views in more than 1500 scans, annotated with 3D camera poses, surface reconstructions, and instance-level semantic segmentations.
To collect this data, we designed an easy-to-use and scalable RGB-D capture system that includes automated surface reconstruction and crowdsourced semantic annotation. 
We show that using this data helps achieve state-of-the-art performance on several 3D scene understanding tasks, including 3D object classification, semantic voxel labeling, and CAD model retrieval.

<img src="img/annotations.png" style="width:500px; display: block; margin-left: auto; margin-right: auto;"/>

## Code and Data:
Please visit our main project repository for more information and access to code and data: [https://github.com/ScanNet/ScanNet](https://github.com/ScanNet/ScanNet)

![](img/voxel-predictions.jpg)
*Semantic voxel labeling of 3D scans in ScanNet using our 3D CNN architecture. Voxel colors indicate predicted or ground truth
category.*

<br>
---
Last updated: 2017-02-16
