# Monocular camera detection

<p align="center">
  <img src="assets/sample_output.gif" alt="example input output gif" width="600" />
</p>

***

This tool combines two algorithms to accurately detect people who are violating the social distancing protocol:
- Facebook/Detectron2 (Faster RCNN implementation)`https://github.com/facebookresearch/detectron2`
- "Digging into Self-Supervised Monocular Depth Prediction" `https://github.com/nianticlabs/monodepth2`

Starter code taken from an excellent tutorial from Aravind Pai:
`https://www.analyticsvidhya.com/blog/2020/05/social-distancing-detection-tool-deep-learning/`

Use:
```
Social-Distance-Tool-with-Depth.ipynb
```

**Libraries needed:**
- Detectron2 = 0.13
- OpenCV >= 3
- Matplotlib
- tqdm
- pytorch = 1.4
- torchvision = 0.4


**Input:**
- A video sequence

**Output:**
- bounding boxes on all persons detected in the video
- highlighing people who are in close proximity
- depth map for accurate calculations 
***

This code is for non-commercial use.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
