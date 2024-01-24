---
layout: archive
title: "Projects"
collection: projects
permalink: /projects/
author_profile: true
---

{% include base_path %}

<div style="display: flex;">
  <div style="flex: 1;">
    <h2>6D Pose Estimation using Iterative Closest Point (ICP) and DenseFusion</h2>
    <p><b>Duration</b>: Oct 2023 - Dec 2023 | 4 mos</p>
    <a href="https://github.com/rohithreddy0087/6D_pose_estimation">Github</a>
    <h3>Outcomes</h3>
    <ul>
        <li>Developed a 6D pose estimation system combining DeepLabv3 for segmentation and Dense Fusion for pose refinement, achieving high accuracy in synthetic scenes with a dataset of 79 object classes./li>
        <li>Conducted extensive training and ablation studies on DeepLabv3 and Dense Fusion, optimizing for accuracy and efficiency; successfully integrated ICP with initial Dense Fusion weights for enhanced pose estimation refinement.</li>
    </ul>
  </div>
</div>

<div style="display: flex;">
  <div style="flex: 1;">
    <h2>Counterfactual Image Generation using Latent Transformations</h2>
    <p><b>Duration</b>: Apr 2023 - Jun 2023 | 4 mos</p>
    <a href="https://github.com/rohithreddy0087/Counter_Factual_Image_Generation">Github</a>
    <h3>Outcomes</h3>
    <ul>
        <li>Developed a pipeline for counterfactual image generation using GANs and neural networks, enabling the creation of visually similar alternative reality images with desired attribute changes for improved image editing and explainable AI.</li>
        <li>Implemented a multi-step process utilizing StyleGAN(trained on CelebA) for random image sampling, attribute classification, and shift prediction to generate high-quality counterfactual images with specified target attributes.</li>
    </ul>
  </div>
</div>

<div style="display: flex;">
  <div style="flex: 1;">
    <h2>Instance Eraser</h2>
    <p><b>Duration</b>: Apr 2023 - Jun 2023 | 4 mos</p>
    <a href="https://github.com/rohithreddy0087/Instance_Eraser">Github</a>
    <h3>Outcomes</h3>
    <ul>
        <li>Developed an algorithm inspired by Google's MagicEraser to remove specified objects from images. Utilized instance segmentation and Pix2Pix GAN model for image reconstruction, achieving contextually relevant background recovery.</li>
        <li>Implemented a user-friendly interface for object removal. Experimented with Mask R-CNN and generative models. While not state of the art, achieved decent results and demonstrated potential for further improvement through experimentation.</li>
    </ul>
  </div>
</div>

<div style="display: flex;">
  <div style="flex: 1;">
    <h2>Hand and Object Segmentation using DeepLabv3</h2>
    <p><b>Duration</b>: Apr 2023 - Jun 2023 | 4 mos</p>
    <a href="https://github.com/rohithreddy0087/Hand_Object_Segmentation">Github</a>
    <h3>Outcomes</h3>
    <ul>
        <li>Developed a hand and object segmentation model for 3D hand pose estimation tasks . Merged hand pose estimation data with segmentation datasets (FreiHand, HO3D, EgoHOS, EgoHands) to create a diverse training dataset.</li>
        <li>Implemented the state-of-the-art DeepLabv3 model with a ResNet backbone and leveraged PyTorch's Distributed Data Parallel for scalability, training on multiple GPUs for over 100,000 training examples. Successfully fine-tuned the model to achieve robust hand and object segmentation, enabling automatic ground truth annotation for 3D hand pose estimation tasks using the HOnnotate method.</li>
    </ul>
  </div>
</div>

<div style="display: flex;">
  <div style="flex: 1;">
    <h2>Data Anaylsis and Website for Smart Building Research</h2>
    <p><b>Duration</b>: Dec 2022 - Mar 2023 | 4 mos</p>
    <a href="https://github.com/rohithreddy0087/smart_building_website">Github</a>
    <h3>Outcomes</h3>
    <ul>
        <li>Developed a website for Smart Building research, featuring a React.js-based frontend seamlessly connected to a Flask API-based backend, with efficient PostgreSQL data storage enhanced by automated table partitioning based on sensor IDs and indexing strategies, ensuring fast data access and retrieval.</li>
        <li>Conducted comprehensive data analysis on sensor data, utilizing data visualization techniques and implemented a basic physics-based neural network computational graph to predict future features, serving as a baseline for subsequent experiments</li>
    </ul>
  </div>
</div>

<div style="display: flex;">
  <div style="flex: 1;">
    <h2>Image Segmentation using Statistical Learning Methods</h2>
    <p><b>Duration</b>: Sept 2022 - Nov 2022 | 3 mos</p>
    <a href="https://github.com/rohithreddy0087/Image_Segmentation_using_Statistical_Learning_Methods">Github</a>
    <h3>Outcomes</h3>
    <ul>
        <li>Developed and implemented statistical learning algorithms in Matlab, including Naive Bayes, Maximum Likelihood Estimation, Bayes Parameter Estimation, and Expectation Maximization, for accurately segmenting a cheetah image into foreground (cheetah) and background (grass) components.</li>
        <li>Evaluated the performance of each algorithm using the probability of error metric, showcasing the effectiveness of more advanced methods like Expectation Maximization in achieving superior segmentation results.</li>
    </ul>
  </div>
</div>

<div style="display: flex;">
  <div style="flex: 1;">
    <h2>Multiple Stream Vehicle Detection and Tracking</h2>
    <p><b>Duration</b>: Aug 2022 - Oct 2022 | 3 mos</p>
    <a href="https://github.com/rohithreddy0087/Multiple_Stream_Vehicle_Detection_and_Tracking">Github</a>
    <h3>Outcomes</h3>
    <ul>
        <li>Developed a GPU-based edge device vehicle detection and tracking system using YOLOv5 and DEEPSORT with the ability to switch between models based on accuracy and live stream requirements.</li>
        <li>Integrated a socket server to broadcast real-time detection data to authenticated clients and deployed a model capable of processing four live streams on a Jetson board with SORT algorithm for tracking.</li>
    </ul>
  </div>
</div>


<div style="display: flex;">
  <div style="flex: 1;">
    <h2>Machine Learning-Based Error Control Code Design for Wireless Channel</h2>
    <p><b>Mentor</b>: Dr. Lakshmi Narasimhan,  IIT Palakkad</p>
    <p><b>Duration</b>: Dec 2020 - May 2021 | 5 mos</p>
    <a href="https://github.com/rohithreddy0087/error-control-codes-wireless-channels">Github</a><br>
    <a href="https://drive.google.com/file/d/1KdAa7BKy_9IJxE1zbGKZgfQDbruOLB7J/view">Report</a>
    <h3>Outcomes</h3>
    <ul>
        <li>Worked on developing error control codes for both block and convolutional codes using end to end deep learning networks on a wireless channel i.e., in both AWGN and Rayleigh channels. </li>
        <li>Demonstrated the ability of neural networks to generate error control codes whose performance was on par with the theoretical error control codes. Training is performed using synthetically curated datasets and TensorFlow2 is used for developing and training the model.</li>
    </ul>
  </div>
</div>

<div style="display: flex;">
  <div style="flex: 1;">
    <h2>Video super-resolution for online video conferencing over low bandwidth network</h2>
    <p><b>Mentor</b>: Dr. Lakshmi Narasimhan,  IIT Palakkad</p>
    <p><b>Duration</b>: Aug 2020 - Nov 2020 | 4 mos</p>
    <a href="https://github.com/rohithreddy0087/Video-superresolution">Github</a> <br>
    <a href="https://drive.google.com/file/d/1hfPK63Mo8h9vhzP7rgASlv2VnhgpIbz0/view">Report</a>
    <h3>Outcomes</h3>
    <ul>
        <li>Worked on developing a Deep-Learning video super-resolution model that can be used in real-time application on a video conferencing platform.</li>
        <li>Employed an Auto-encoder model that was able to convert 144p to 480p resolution with good accuracy. The whole framework is implemented using PyTorch on a GPU. Datasets are gathered using an automated system from YouTube using Python and Google API services.</li>
    </ul>
  </div>
</div>

<div style="display: flex;">
  <div style="flex: 1;">
    <h2>Software Defined Radio for Visible Light Communication</h2>
    <p><b>Mentor</b>: Dr. Lakshmi Narasimhan,  IIT Palakkad</p>
    <p><b>Duration</b>: Jan 2020 - Mar 2020 | 3 mos</p>
    <a href="https://drive.google.com/file/d/1vdXjsjnN00gCTreY7MXLHa3RjJzY1t0D/view">Report</a>
    <h3>Outcomes</h3>
    <ul>
        <li>Developed an Open SDR to aid the research in visible light communication. The open source SDR invites people to experiment with the setup. We developed software using Python Tkinter and matplotlib to make a GUI for SDR and implemented a hardware model using LEDs and phototransistors.</li>
        <li>We were able to transfer data but with very low bit rates. Hence, we designed a more efficient model to increase the bit rates but couldn’t implement it because of Covid-19 restrictions</li>
    </ul>
  </div>
</div>

<div style="display: flex;">
  <div style="flex: 1;">
    <h2>Raspberry Pi keyboard as Bluetooth joystick for Toycar </h2>
    <p><b>Mentor</b>: Dr. G V V Sharma, IIT Hyderabad</p>
    <p><b>Duration</b>: May 2019 - Jun 2019 | 2 mos</p>
    <a href="https://github.com/rohithreddy0087/toy-car-using-bluetooth-raspberry-pi">Github</a>
    <h3>Outcomes</h3>
    <ul>
        <li>Making of a toycar using a toycar kit and arduino and then controlling the toycar with a joystick made with raspberry pi and a keyboard attached with it.</li>
        <li>Data is transmitted from bluetooth raspberry pi and recieved using a bluetooth module attached to arduino and code for serial transmission.</li>
    </ul>
  </div>
</div>


<div style="display: flex;">
  <div style="flex: 1;">
    <h2> OpenCV based Face Recognition System</h2>
    <p><b>Mentor</b>: Dr. Jobin Francis,  IIT Palakkad</p>
    <p><b>Duration</b>: Mar 2019 - Apr 2019 | 2 mos</p>
    <a href="https://drive.google.com/file/d/1iE-mWUr_SYXUnVDcc2hRHg2E72ReAH6K/view">Report</a>
    <h3>Outcomes</h3>
    <ul>
        <li>Built an OpenCV based face detection system that acquires a video and automatically recognizes faces.</li>
        <li>The developed code uses Python OpenCV module and efficiently trained Caffe models to detect the features of a face and recognize them in the frame with 70% probability</li>
    </ul>
  </div>
</div>

<div style="display: flex;">
  <div style="flex: 1;">
    <h2>Broken Wire Detector - PCB</h2>
    <p><b>Mentor</b>: Dr. Revathy Padmanabam, IIT Palakkad</p>
    <p><b>Duration</b>: Jan 2019 - Apr 2019 | 4 mos</p>
    <a href="https://drive.google.com/file/d/1HyJg5R_4P0HfQ0p77pnHotexIjPv8I1d/view">Report</a>
    <h3>Outcomes</h3>
    <ul>
        <li>Designed and fabricated a PCB circuit using traditional techniques such as manual routing, toner transfer, etching and soldering</li>
        <li>The developed PCB circuit detects a broken or faulty wire using the EMF generated by an alternating current without physically disturbing wires. </li>
    </ul>
  </div>
</div>

<!-- <div style="display: flex;">
  <div style="flex: 1;">
    <h2>Smart Cities: Garbage Management System - Digital Systems</h2>
    <p><b>Mentor</b>: Dr. Sabu Emmanuel,  IIT Palakkad</p>
    <p><b>Duration</b>: Oct 2018 - Nov 2018 | 2 mos</p>
    <h3>Outcomes</h3>
    <ul>
        <li>Main objective of the project is to make a prototype for efficient garbage management system that connects a range of places in a city.</li>
        <li>The developed prototype is written in Verilog and implemented on a Xilinx- Zynq FPGA board</li>
    </ul>
  </div>
</div> -->
