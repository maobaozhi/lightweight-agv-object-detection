# Lightweight Feature Fusion and Adaptive Upsampling for Real-Time Warehouse AGV Object Detection

## Overview

This repository accompanies the research manuscript entitled **"Lightweight Feature Fusion and Adaptive Upsampling for Real-Time Warehouse AGV Object Detection"**.

The research focuses on efficient object detection for warehouse automated guided vehicles (AGVs), particularly lightweight feature fusion and adaptive upsampling techniques.

## Datasets

All datasets used in this study are publicly available from their original sources.

### 1. Warehouse Dataset

The warehouse object detection dataset is provided by **Addverb Technologies** through Roboflow Universe.

- **Dataset:** Warehouse
- **Version:** 1
- **Task:** Object Detection
- **Source:** [Roboflow Universe — Warehouse Dataset](https://universe.roboflow.com/addverb-technologies/warehouse-ijyxt/dataset/1)

### 2. PASCAL VOC 2007+2012

The PASCAL VOC benchmark used in this study combines data from the official VOC2007 and VOC2012 releases. It contains **21,503 images** covering **20 object categories**.

The dataset is constructed from three official archives:

- `VOCtrainval_06-Nov-2007.tar` — 5,011 training/validation images.
- `VOCtrainval_11-May-2012.tar` — 11,540 training/validation images.
- `VOCtest_06-Nov-2007.tar` — 4,952 test images.

The training set combines VOC2007 trainval and VOC2012 trainval, comprising **16,551 images**. The **4,952 VOC2007 test images** are used as the evaluation set.

Official dataset sources:

- [PASCAL VOC2007](https://www.robots.ox.ac.uk/~vgg/projects/pascal/VOC/voc2007/)
- [PASCAL VOC2012](https://www.robots.ox.ac.uk/~vgg/projects/pascal/VOC/voc2012/)

## Code Availability

The source code associated with this research will be made publicly available in this repository upon acceptance of the manuscript.

## Authors

- Guorui Liu
- Zehao Zhao
- Hualin Dai
- Yurong Xue
- Yegui Lin

**Corresponding Author:** Hualin Dai

**Affiliation:** Tianjin Chengjian University, Tianjin, China

**Contact:** daihualin@tcu.edu.cn

## Acknowledgments

The authors acknowledge Addverb Technologies and the PASCAL VOC organizers for making their datasets publicly available.
