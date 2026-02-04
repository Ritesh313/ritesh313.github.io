---
permalink: /key_projects/
title: "Key Projects"

excerpt: "Ritesh Chowdhry Key Projects"
layout: single
author_profile: true
sitemap: true
modified: 2026-02-04
---

## NeonTreeClassification Package
*Google Summer of Code 2025*

An open-source Python package for ecological research enabling multimodal tree species classification using NEON data. The package provides:
- Comprehensive dataset of 167 tree species with 47,971 individual tree crowns
- RGB imagery, 369-band hyperspectral data, and LiDAR canopy height models
- End-to-end data pipeline for automated downloading, cropping, and curation
- Pretrained classification models and preprocessing workflows

[GitHub Repository](https://github.com/Ritesh313/NeonTreeClassification)

---

## Multistream Architecture for Repetitive Action Counting

Created a multi-stream architecture utilizing RGB (using [MoviNets](https://arxiv.org/abs/2103.11511) backbone) and pose estimation (poses extracted using [YOLOv7](https://arxiv.org/abs/2207.02696)) techniques to accurately count the number of repetitions performed during exercise routines, as well as to effectively classify the specific exercises being executed.

**Key Features:**
- Multi-modal approach combining RGB video and pose estimation
- Real-time repetition counting
- Exercise classification capability

---

## Indian Licence Plate Recognition System

Developed an Automatic Number Plate Recognition (ANPR) system for Indian license plates that classifies vehicle, plate type (back/front) and characters using a single model, achieving 25 fps performance. The dataset and code were made publicly available to facilitate future research.

**Technical Approach:**
- Two-stage model combining semantic segmentation for localization with LPRNet for character recognition
- Novel annotation technique to handle different plate orientations
- Released comprehensive dataset for Indian license plates in the wild

[arXiv Paper](https://arxiv.org/abs/2111.06054)

---

## F1-tenth Self-Driving Car
*September 2019 - December 2020*

Implemented and designed self-driving algorithms including wall following, mapping & localization, and path planning using SLAM for a one-tenth model of an F1 car.

**Technologies Used:**
- LiDAR and stereo camera sensors
- ROS (Robot Operating System)
- NVIDIA Jetson TX-2 as SOC Board
- SLAM for mapping and localization

Based on the [UPenn F1tenth project](https://f1tenth.org/)
