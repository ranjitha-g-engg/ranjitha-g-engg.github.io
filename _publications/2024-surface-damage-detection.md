---
title: "2D Image and CNN-Based Approach for Automated Surface Damage Detection on Aircraft Surface"
collection: publications
category: manuscripts
permalink: /publication/2024-surface-damage-detection
excerpt: 'Research on automated defect detection for aerospace applications using computer vision and deep learning.'
date: 2024-11-01
venue: 'Under Review'
paperurl: ''
citation: 'Ranjitha G. et al. (2024). "2D Image and CNN-Based Approach for Automated Surface Damage Detection on Aircraft Surface." Under Review.'
---

## Abstract

This research presents a novel approach for automated surface damage detection on aircraft surfaces using 2D image processing and Convolutional Neural Networks (CNN). The system combines traditional computer vision techniques with deep learning to achieve high accuracy in identifying various types of surface defects.

## Key Contributions

- **Multi-Modal Detection Pipeline**: Hybrid approach combining 2D computer vision (YOLOv8) and 3D point cloud analysis (PointNet)
- **100% Accuracy**: Achieved on industrial aerospace datasets
- **Real-time Processing**: Sub-100ms latency for production deployment
- **Automated Workflow**: Reduced manual inspection time by 70%

## Methodology

### Data Collection
- 10,000+ high-resolution images
- 1,000+ 3D point cloud scans
- Multiple defect types: dents, rivets, scratches, corrosion

### Model Architecture
- YOLOv8 for 2D object detection (88.57% accuracy)
- PointNet for 3D geometric analysis (100% accuracy)
- Custom cross-model Non-Maximum Suppression (NMS)

### Results
- **Detection Accuracy**: 100% on 3D defects
- **Precision Improvement**: 35% over baseline
- **Inference Speed**: 30 FPS real-time processing
- **Deployment**: Raspberry Pi edge device

## Applications

- Aircraft maintenance and inspection
- Non-Destructive Testing (NDT)
- Quality control in aerospace manufacturing
- Automated defect documentation

## Technologies

`YOLOv8` `PointNet` `PyTorch` `Open3D` `Computer Vision` `Deep Learning` `Edge Computing`

---

**Status**: Under Review  
**Organization**: CSIR-National Aerospace Laboratories  
**Year**: 2024

[Download Preprint](#){: .btn .btn--primary} *(Available upon publication)*
