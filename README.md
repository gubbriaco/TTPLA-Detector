# TTPLA Detector: Detection and Segmentation of Transmission Towers and Power Lines

Welcome to the TTPLA Detector repository! This project provides tools and models to detect and segment transmission towers and power lines from aerial imagery. The main focus is to enhance the automation of electrical infrastructure monitoring, especially for power transmission lines, by leveraging state-of-the-art computer vision techniques.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Trained Model](#trained-model)

## Introduction

Power transmission lines and towers play a crucial role in energy distribution networks. Regular monitoring of these structures is essential for maintaining safety and efficiency. However, manual inspection is labor-intensive and time-consuming. **TTPLA Detector** aims to automate this process through computer vision by detecting and segmenting both transmission towers and power lines in aerial images.

## Features

- **Transmission Tower Detection**: Accurately identifies and localizes transmission towers in aerial images.
- **Power Line Segmentation**: Segments power lines with high precision.
- **Customizable Model Architecture**: Flexibility to choose different backbone architectures and hyperparameters for model training.
- **Preprocessing and Augmentation**: Provides image preprocessing and data augmentation utilities to improve model robustness.

## Dataset

The following Google Drive link allows access to the initial dataset: [TTPLA Dataset (trainingset and testset)](https://drive.google.com/file/d/1t4ZCts89QfMgsqhJq9Jkmm-VofpgeWCT/view?usp=sharing)

On the other hand, the following Google Drive link allows consulting the augmented trainingset: [TTPLA Dataset (trainingset augmented)](https://drive.google.com/file/d/1G6uVqmZbZNwoPqL1YxAQutj2VcYSsetW/view?usp=sharing)

## Installation

To use this repository, clone it and install the dependencies:

```bash
git clone https://github.com/gubbriaco/TTPLA-Detector.git
cd TTPLA-Detector
```

The dependencies will be installed automatically through Installer class (see inside ttpla-detectron2-mask-rcnn-trainer, ttpla-detectron2-mask-rcnn-tester, ttpla-detectron2-mask-rcnn-evaluator).

## Trained Model
The following Google Drive link allows access to the TTPLA trained model: [TTPLA Trained Model](https://drive.google.com/file/d/1wb6ttjP_-1OEZaCvk0aBWIYVlt_U3fIH/view?usp=sharing)
