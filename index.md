[//]: # (# ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes)

<h3 align="center">
<a href="http://cs.stanford.edu/~adai/publications.html">Angela Dai</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://angelxuanchang.github.io">Angel X. Chang</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://msavva.github.io">Manolis Savva</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="http://www.cs.princeton.edu/~mhalber/">Maciej Halber</a><br><a href="http://www.cs.princeton.edu/~funk/">Thomas Funkhouser</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="http://graphics.stanford.edu/~niessner/publications.html">Matthias Nie&szlig;ner</a>
</h3>

<h4 align="center">
 Stanford University&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Princeton University
</h4>

ScanNet is an RGB-D video dataset containing 2.5 million views in more than 1500 scans, annotated with 3D camera poses, surface reconstructions, and instance-level semantic segmentations.
To collect this data, we designed an easy-to-use and scalable RGB-D capture system that includes automated surface reconstruction and crowdsourced semantic annotation. 
We show that using this data helps achieve state-of-the-art performance on several 3D scene understanding tasks, including 3D object classification, semantic voxel labeling, and CAD model retrieval.
More information can be found in our <a href="https://arxiv.org/abs/1702.04405">paper</a>.

<a href="https://arxiv.org/abs/1702.04405">
<img src="img/annotations.png" style="width:500px; display: block; margin-left: auto; margin-right: auto;"/>
</a>

If you use the ScanNet data or code please cite:
```
@article{dai2017scannet,
    title={ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes},
    author={Dai, Angela and Chang, Angel X. and Savva, Manolis and Halber, Maciej and Funkhouser, Tom and Nie{\ss}ner, Matthias},
    journal={arXiv preprint arXiv:1702.04405},
    year={2017}
}
```

## Code and Data:
Please visit our main project repository for more information and access to code and data: [https://github.com/ScanNet/ScanNet](https://github.com/ScanNet/ScanNet)

<a href="img/voxel-predictions.jpg">
<img src="img/voxel-predictions.jpg" style="width:600px; display: block; margin-left: auto; margin-right: auto;"/>
</a>
*Semantic voxel labeling of 3D scans in ScanNet using our 3D CNN architecture. Voxel colors indicate predicted or ground truth
category.*

<br>
---
Last updated: 2017-02-17
