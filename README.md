# Social Distance Tool with depth

This tool combines two algorithms to accurately detect people who are violating the social distancing protocol:
- Facebook/Detectron2 (Faster RCNN implementation)`https://github.com/facebookresearch/detectron2`
- "Digging into Self-Supervised Monocular Depth Prediction" `https://github.com/nianticlabs/monodepth2`

Starter code taken from an excellent tutorial from Aravind Pai:
`https://www.analyticsvidhya.com/blog/2020/05/social-distancing-detection-tool-deep-learning/`

Use:
```
Social-Distance-Tool-with-Depth.ipynb
```

**Input:**
- A video sequence

**Output:**
- bounding boxes on all persons detected in the video
- highlighing people who are in close proximity
- depth map for accurate calculations 
***

<p align="center">
  <img src="assets/sample_output.gif" alt="example input output gif" width="600" />
</p>

This code is for non-commercial use.
