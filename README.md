# Lightweight Feature Fusion and Adaptive Upsampling for Real-Time Warehouse AGV Object Detection

## Overview

This repository accompanies the research manuscript entitled **"Lightweight Feature Fusion and Adaptive Upsampling for Real-Time Warehouse AGV Object Detection"**, prepared for the *Journal of Electronic Imaging (JEI)*, published by SPIE.

The study focuses on efficient and lightweight object detection for warehouse automated guided vehicles (AGVs), with particular emphasis on feature fusion, adaptive upsampling, and real-time detection performance.

The experiments are conducted using two publicly available datasets: **Warehouse-ijyxt** and **PASCAL VOC 2007+2012**.

## Datasets

All datasets used in this study are publicly available from their original sources. The dataset descriptions and experimental partitions are provided below to facilitate research transparency and reproducibility.

### 1. Warehouse-ijyxt Dataset

The **Warehouse-ijyxt** dataset, published by **Addverb Technologies** on the **Roboflow Universe** platform, is designed for object detection in warehouse and logistics environments.

The generated dataset **Version 1** comprises **21,564 images** covering seven categories of dynamic and static objects commonly encountered in warehouse operations.

The seven object categories are:

1. Forklift
2. Pallet
3. Cart
4. Ladder
5. Autonomous Mobile Robot (AMR)
6. Pallet Jack
7. Person

The dataset follows the official Version 1 partitioning scheme:

| Dataset Split | Number of Images |
|---|---:|
| Training | 19,967 |
| Validation | 1,185 |
| Testing | 412 |
| **Total** | **21,564** |

This dataset is used to evaluate object detection performance in warehouse environments, including the recognition of vehicles, equipment, and personnel.

**Dataset Information:**

- **Dataset Name:** Warehouse-ijyxt
- **Publisher:** Addverb Technologies
- **Platform:** Roboflow Universe
- **Dataset Version:** 1
- **Task:** Object Detection
- **Number of Classes:** 7
- **Number of Images:** 21,564
- **License:** CC BY 4.0

**Official Dataset Link:**

[Warehouse-ijyxt Dataset — Roboflow Universe (Version 1)](https://universe.roboflow.com/addverb-technologies/warehouse-ijyxt/dataset/1)

### 2. PASCAL VOC 2007+2012 Dataset

The **PASCAL Visual Object Classes (VOC)** dataset is a widely used benchmark for object detection and recognition.

In this study, the PASCAL VOC dataset is constructed using the officially released **VOC2007** and **VOC2012** datasets.

The combined dataset contains **21,503 images** covering **20 object categories**, including persons, airplanes, bicycles, cars, chairs, dogs, and television monitors.

The dataset is constructed from the following official releases:

| Official Dataset Archive | Number of Images | Usage |
|---|---:|---|
| VOCtrainval_06-Nov-2007.tar | 5,011 | Training |
| VOCtrainval_11-May-2012.tar | 11,540 | Training |
| VOCtest_06-Nov-2007.tar | 4,952 | Evaluation |
| **Total** | **21,503** | |

**Training Set**

The training set combines:

- VOC2007 trainval
- VOC2012 trainval

The resulting training set contains **16,551 images**.

**Evaluation Set**

The evaluation set uses the **VOC2007 test** partition, containing **4,952 images**.

The PASCAL VOC benchmark includes the following 20 object categories:

- Aeroplane
- Bicycle
- Bird
- Boat
- Bottle
- Bus
- Car
- Cat
- Chair
- Cow
- Dining Table
- Dog
- Horse
- Motorbike
- Person
- Potted Plant
- Sheep
- Sofa
- Train
- TV/Monitor

**Official Dataset Links:**

- [PASCAL VOC Project](https://www.robots.ox.ac.uk/~vgg/projects/pascal/VOC/)
- [PASCAL VOC2007](https://www.robots.ox.ac.uk/~vgg/projects/pascal/VOC/voc2007/)
- [PASCAL VOC2012](https://www.robots.ox.ac.uk/~vgg/projects/pascal/VOC/voc2012/)

## Data Availability

All datasets used in this study are publicly available through their original providers.

The Warehouse-ijyxt dataset can be accessed through Roboflow Universe, while the PASCAL VOC2007 and VOC2012 datasets can be obtained from the official PASCAL VOC website.

The original datasets are not redistributed in this repository. Researchers should obtain them directly from their respective providers and comply with the applicable dataset licenses and terms of use.

## Code Availability

The source code associated with this research is not publicly available during the manuscript review process.

**The complete implementation will be released in this GitHub repository upon acceptance of the manuscript.**

The future release is intended to include the relevant implementation and instructions necessary to reproduce the experiments.

## Authors

- Guorui Liu
- Zehao Zhao
- Hualin Dai
- Yurong Xue
- Yegui Lin

**Corresponding Author:** Hualin Dai

**Affiliation:** Tianjin Chengjian University, Tianjin, China

**Email:** daihualin@tcu.edu.cn

## Acknowledgments

The authors gratefully acknowledge **Addverb Technologies** and the **PASCAL VOC organizers** for making their datasets publicly available.

These resources provide valuable benchmarks for evaluating object detection algorithms in warehouse and general object detection scenarios.

## Publication Information

**Manuscript Title:** Lightweight Feature Fusion and Adaptive Upsampling for Real-Time Warehouse AGV Object Detection

**Target Journal:** Journal of Electronic Imaging (SPIE)

Publication details and citation information will be updated when available.
