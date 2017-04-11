[//]: # (# ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes)

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-77156287-3', 'auto');
  ga('send', 'pageview');

</script>

<h3 align="center">
<a href="http://cs.stanford.edu/~adai/publications.html">Angela&nbsp;Dai</a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://angelxuanchang.github.io">Angel&nbsp;X.&nbsp;Chang</a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://msavva.github.io">Manolis&nbsp;Savva</a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="http://www.cs.princeton.edu/~mhalber/">Maciej&nbsp;Halber</a><br><a href="http://www.cs.princeton.edu/~funk/">Thomas&nbsp;Funkhouser</a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="http://graphics.stanford.edu/~niessner/publications.html">Matthias&nbsp;Nie&szlig;ner</a>
</h3>

<h4 align="center">
 Stanford University&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Princeton University&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Technical University of Munich
</h4>

<a href="http://www.youtube.com/watch?v=Olx4OnoZWQQ">
<img src="img/vid.jpg" alt="ScanNet" style="width:400px; display: block; margin-left: auto; margin-right: auto;"/>
</a>
<br>

ScanNet is an RGB-D video dataset containing 2.5 million views in more than 1500 scans, annotated with 3D camera poses, surface reconstructions, and instance-level semantic segmentations.
To collect this data, we designed an easy-to-use and scalable RGB-D capture system that includes automated surface reconstruction and crowdsourced semantic annotation. 
We show that using this data helps achieve state-of-the-art performance on several 3D scene understanding tasks, including 3D object classification, semantic voxel labeling, and CAD model retrieval.
More information can be found in our <a href="https://arxiv.org/abs/1702.04405">paper</a>.

<a href="https://arxiv.org/abs/1702.04405">
<img src="img/annotations.png" style="width:640px; display: block; margin-left: auto; margin-right: auto;"/>
</a>

If you use the ScanNet data or code please cite:
```
@article{dai2017scannet,
    title={ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes},
    author={Dai, Angela and Chang, Angel X. and Savva, Manolis and Halber, Maciej and Funkhouser, Thomas and Nie{\ss}ner, Matthias},
    journal={arXiv preprint arXiv:1702.04405},
    year={2017}
}
```

## License
The data is released under a <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 License</a>. 

## Code and Data:
Please visit our main project repository for more information and access to code and data: [https://github.com/ScanNet/ScanNet](https://github.com/ScanNet/ScanNet)

<a href="img/voxel-predictions.jpg">
<img src="img/voxel-predictions.jpg" style="width:640px; display: block; margin-left: auto; margin-right: auto;"/>
</a>
*Semantic voxel labeling of 3D scans in ScanNet using our 3D CNN architecture. Voxel colors indicate predicted or ground truth
category.*

<br>
---
Last updated: 2017-02-17
