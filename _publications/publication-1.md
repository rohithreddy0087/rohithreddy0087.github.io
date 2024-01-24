---
title: "Hand-Drawn Electrical Circuit Recognition using Object Detection and Node Recognition"
collection: publications
permalink: /publications/
excerpt: 'This project proposes a real-time algorithm for the automatic recognition of hand-drawn electronic circuits and subsequently rebuilds the circuit schematic based on object detection and circuit node recognition'
date: 2022-04-25
venue: 'SN Computer Science'
paperurl: 'https://link.springer.com/article/10.1007/s42979-022-01159-0'
citation: 'Rachala, R.R., Panicker, M.R. Hand-Drawn Electrical Circuit Recognition Using Object Detection and Node Recognition. SN COMPUT. SCI. 3, 244 (2022). https://doi.org/10.1007/s42979-022-01159-0'
---
With the recent developments in neural networks, there has been a resurgence in algorithms for the automatic generation of simulation ready electronic circuits from hand-drawn circuits. However, most of the approaches in the literature were confined to classify different types of electrical components. Only a few of those methods have shown a way to rebuild the circuit schematic from the scanned image, which is extremely important for further automation of netlist generation. This paper proposes (1) a real-time algorithm for the automatic recognition of hand-drawn electronic circuits and (2) subsequently rebuild the circuit schematic based on object detection and circuit node recognition. The automatic recognition employs light weight and popular you only look once version 5 (YOLOv5) for detection of circuit components and a novel Hough transform-based approach for node recognition. Using YOLOv5 object detection algorithm, a mean average precision (mAP0.5) of 98.2% is achieved in detecting the components. The proposed method is also able to rebuild the circuit schematic with 80% accuracy with a near-real-time performance of 0.33 s per schematic generation.

[Download paper here](https://link.springer.com/article/10.1007/s42979-022-01159-0)<br>
[Github link](https://github.com/rohithreddy0087/Hand-Drawn-Electrical-Circuit-Recognition-using-YOLOv5)