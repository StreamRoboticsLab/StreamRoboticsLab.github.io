---
title: "RoboticsXR: Extended Reality for Robotics Visual Navigation"
layout: default
---

## Authors

<div style="text-align: center;">
  <a href="https://www.polito.it/personale?p=petre.ricioppo">Petre Ricioppo</a>, 
  <a href="https://www.polito.it/personale?p=riccardo.enrico">Riccardo Enrico</a>, 
  <a href="https://www.polito.it/personale?p=jeanluc.sarvadon">Jean-Luc Sarvadon</a>, 
  <a href="https://www.polito.it/personale?p=dario.ruggiero">Dario Ruggiero</a>, and 
  <a href="https://www.polito.it/personale?p=elisa.capello">Elisa Capello</a>

  <br><br>

  <!-- Subsubsection for Affiliations -->
  <div style="text-align: center; font-size: 0.9em;">
    <strong>Affiliations:</strong>
    <br>
    All authors are affiliated with <em>Stream Robotics Lab, Politecnico di Torino</em>.
  </div>
</div>

## Abstract

<div style="text-align: justify;">
  Virtual Environments and Extended Reality (XR) have transformed artificial intelligence and robotics research by enabling realistic simulations for training and testing. XR enable the seamless integration of digital and physical spaces, offering new opportunities for training and testing autonomous systems. In this work, we propose RoboticsXR, an XR-based framework where a robot operates in a physical lab while images are captured from a virtual environment. This approach fuses real-world motion with synthetic visual data to develop and validate visual navigation algorithms efficiently. RoboticsXR is evaluated using a convolutional neural network trained on synthetic images from NVIDIA Isaac, assessing its performance across different hardware platforms and lighting conditions. Results highlight its potential to extend laboratory testing capabilities, reducing costs and improving the reliability of vision-based navigation systems.
</div>

# Video

<video width="100%" height="auto" controls>
  <source src="./media/RoboticsXRIROS.mp4" type="video/mp4">
</video>

## Description

<div style="text-align: justify;">
RoboticsXR is an extended reality framework that fuses real-world robot motion with synthetic visual data. It uses ROS2 to integrate a YOLOv8-based detection system and a ResNet50 network for precise distance estimation, enabling efficient testing of visual navigation algorithms across varied hardware and lighting conditions.
</div>
