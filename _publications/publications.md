---
layout: archive
title: "Publications"
collection: publications
permalink: /publications/
author_profile: true
---

{% include base_path %}

<div style="display: flex;">
  <div style="flex: 1;">
    <h2>Hand-Drawn Electrical Circuit Recognition using Object Detection and Node Recognition</h2>
    <p><b>Date</b>: 2022-04-25</p>
    <p><b>Venue</b>: SN Computer Science</p>
    <a href="https://link.springer.com/article/10.1007/s42979-022-01159-0">Paper url</a>
    <a href="https://github.com/rohithreddy0087/Hand-Drawn-Electrical-Circuit-Recognition-using-YOLOv5">Github</a>
    
    <p><b>Citation</b>: Rachala, R.R., Panicker, M.R. Hand-Drawn Electrical Circuit Recognition Using Object Detection and Node Recognition. SN COMPUT. SCI. 3, 244 (2022). https://doi.org/10.1007/s42979-022-01159-0</p>
    <h3>Abstract</h3>
    With the recent developments in neural networks, there has been a resurgence in algorithms for the automatic generation of simulation ready electronic circuits from hand-drawn circuits. However, most of the approaches in the literature were confined to classify different types of electrical components. Only a few of those methods have shown a way to rebuild the circuit schematic from the scanned image, which is extremely important for further automation of netlist generation. This paper proposes (1) a real-time algorithm for the automatic recognition of hand-drawn electronic circuits and (2) subsequently rebuild the circuit schematic based on object detection and circuit node recognition. The automatic recognition employs light weight and popular you only look once version 5 (YOLOv5) for detection of circuit components and a novel Hough transform-based approach for node recognition. Using YOLOv5 object detection algorithm, a mean average precision (mAP0.5) of 98.2% is achieved in detecting the components. The proposed method is also able to rebuild the circuit schematic with 80% accuracy with a near-real-time performance of 0.33 s per schematic generation.
  </div>
</div>

<div style="display: flex;">
  <div style="flex: 1;">
    <h2>BEAR-Data: Analysis and Applications of an Open Multizone Building Dataset</h2>
    <p><b>Date</b>: 2023-09-07</p>
    <p><b>Venue</b>: ACM BuildSys-23</p>
    <a href="https://dl.acm.org/doi/abs/10.1145/3600100.3623740">Paper url</a>
    <a href="https://ucsdsmartbuilding.github.io/index.html">Github</a>
    
    <p><b>Citation</b>: Yuexin Bian, Xiaohan Fu, Bo Liu, Rohith Rachala, Rajesh K. Gupta, and Yuanyuan Shi. 2023. BEAR-Data: Analysis and Applications of an Open Multizone Building Dataset. In Proceedings of the 10th ACM International Conference on Systems for Energy-Efficient Buildings, Cities, and Transportation (BuildSys '23). Association for Computing Machinery, New York, NY, USA, 240–243. https://doi.org/10.1145/3600100.3623740</p>
    <h3>Abstract</h3>
    We introduce BEAR-Data, an open dataset that captures the dynamics of a large multi-zone building by providing measurements of zone temperature and corresponding HVAC (Heating, Ventilation, and Air Conditioning) control actions for over 80 thermal zones. This paper presents a detailed description of the dataset’s collection process and features, and data analysis of system utilization and building thermal patterns. To showcase the dataset’s usefulness, we demonstrate one potential application of thermal dynamic identification and discuss how the released dataset supports various applications in building research, such as energy consumption forecasting, model-based control, and building performance benchmarking. We envision that the availability of this work can foster innovation and drive improvements in building energy systems.
  </div>
</div>
