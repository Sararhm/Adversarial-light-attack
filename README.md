# Infrared Laser Reflection Attack Against Traffic Sign Recognition Systems

## Overview

This project explores the vulnerability of Traffic Sign Recognition (TSR) systems to adversarial attacks using infrared (IR) laser reflections. TSR systems are critical components of Advanced Driver Assistance Systems (ADAS) and autonomous vehicles, relying on accurate detection and classification of traffic signs. This project demonstrates how IR laser reflections can be used to manipulate the input of TSR systems, causing them to misclassify or fail to detect traffic signs, potentially leading to safety hazards.

## Features

- **Infrared Laser Attack Simulation:** Implementation of IR laser reflection attacks targeting TSR systems, with a focus on causing misclassification of traffic signs.
- **Traffic Sign Dataset Integration:** Utilization of standard traffic sign datasets (e.g., GTSRB) for testing the impact of IR laser reflection on TSR models.
- **Model Training and Evaluation:** Training and evaluation of state-of-the-art TSR models (e.g., YOLO, Faster R-CNN) to assess their robustness against the proposed attack.
- **Adversarial Example Generation:** Generation of adversarial traffic sign images using simulated IR laser reflections.
- **Performance Metrics:** Evaluation of the attack's effectiveness using metrics such as classification accuracy, detection rate, and misclassification rate.


## Examination and Results

As part of this project, I conducted a thorough examination of the vulnerability of Traffic Sign Recognition (TSR) systems to infrared laser reflection attacks. The examination involved the following steps:

1. **Model Training:** I trained a YOLO-based TSR model using the prepared traffic sign dataset. The model was optimized for accurate detection and classification of traffic signs in various conditions.

2. **Attack Simulation:** I simulated the infrared laser reflection attack on a selection of test images from the dataset. The simulation aimed to create adversarial examples by reflecting IR laser light onto the traffic signs, distorting the visual input to the TSR system.

3. **Running YOLO:** The trained YOLO model was then used to process both the clean and adversarial images. The goal was to observe the model's behavior when subjected to the IR laser reflection attack and to quantify the impact on detection accuracy.

4. **Results Documentation:** The photos that were tested, including both clean and adversarial examples, along with their detection outcomes, are saved in the `results/` directory. These results showcase the effectiveness of the attack, with clear instances of misclassified or undetected traffic signs.

The findings from this examination provide insights into the weaknesses of current TSR systems when exposed to IR laser reflection, highlighting the need for improved robustness in real-world applications.
