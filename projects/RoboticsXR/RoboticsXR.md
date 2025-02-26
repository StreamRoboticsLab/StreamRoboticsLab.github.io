# RoboticsXR: Extended Reality for Robotics Visual Navigation

## Authors

- [Petre Ricioppo](https://www.polito.it/personale?p=petre.ricioppo)
- [Riccardo Enrico](https://www.polito.it/personale?p=riccardo.enrico)
- [Jean-Luc Sarvadon](https://www.polito.it/personale?p=jeanluc.sarvadon)
- [Dario Ruggiero](https://www.polito.it/personale?p=dario.ruggiero)
- [Elisa Capello](https://www.polito.it/personale?p=elisa.capello)

## Abstract

Virtual Environments and Extended Reality (XR) have transformed artificial intelligence and robotics research by enabling realistic simulations for training and testing. XR enable the seamless integration of digital and physical spaces, offering new opportunities for training and testing autonomous systems. In this work, we propose RoboticsXR, an XR-based framework where a robot operates in a physical lab while images are captured from a virtual environment. This approach fuses real-world motion with synthetic visual data to develop and validate visual navigation algorithms efficiently. RoboticsXR is evaluated using a convolutional neural network trained on synthetic images from NVIDIA Isaac, assessing its performance across different hardware platforms and lighting conditions. Results highlight its potential to extend laboratory testing capabilities, reducing costs and improving the reliability of vision-based navigation systems.

# Video

<video width="100%" height="auto" controls>
  <source src="./media/RoboticsXRIROS.mp4" type="video/mp4">
</video>

## Description

RoboticsXR is an extended reality framework that fuses real-world robot motion with synthetic visual data. It uses ROS2 to integrate a YOLOv8-based detection system and a ResNet50 network for precise distance estimation, enabling efficient testing of visual navigation algorithms across varied hardware and lighting conditions.