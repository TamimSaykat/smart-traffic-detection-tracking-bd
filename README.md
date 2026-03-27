# Bangladesh Traffic ODT

<p align="center">
  <b>Object Detection and Multi-Object Tracking for Bangladesh Traffic Scenes</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Computer%20Vision-Object%20Detection-2563eb?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Multi--Object-Tracking-7c3aed?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Dataset-Bangladesh%20Traffic-059669?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Framework-Python-f59e0b?style=for-the-badge" />
</p>

---

## Overview

**Bangladesh Traffic ODT** is a computer vision pipeline for **object detection** and **multi-object tracking** in dense, unstructured Bangladesh traffic environments.  
It covers the full workflow from **annotation conversion** and **data preprocessing** to **model training**, **tracking**, and **performance analysis**.

---

## Key Features

- Pascal VOC to YOLO annotation conversion  
- Group-aware train/validation/test split  
- Bounding-box-safe offline augmentation  
- YOLO and COCO-style dataset export  
- Detector training and validation  
- Multi-object tracker benchmarking  
- Reproducible experiment artifacts and analysis  

---

## Dataset

This project uses the **Bangladesh Traffic Flow Dataset**:

- [Kaggle Dataset](https://www.kaggle.com/datasets/ari7889/bangladesh-traffic)

**Classes:** `cng`, `rickshaw`, `car`, `bus`, `bike`, `people`, `mini-truck`, `cycle`, `truck`

---

## Tech Stack

- **Detection:** YOLO26, RF-DETR  
- **Tracking:** SORT, ByteTrack, BoT-SORT, SimpleIoU  
- **Data Processing:** Albumentations, COCO / YOLO export  
- **Environment:** Python, Kaggle / local execution  

---

## Project Structure

```bash
bangladesh-traffic-odt/
├── notebooks/
├── configs/
├── src/
├── data/
├── outputs/
├── README.md
├── requirements.txt
└── LICENSE
