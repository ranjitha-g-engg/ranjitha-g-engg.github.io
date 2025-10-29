---
title: "3D Vision & Depth Estimation Pipeline"
excerpt: "Advanced point cloud processing achieving 95.8% depth accuracy<br/><img src='https://via.placeholder.com/600x300/6c5ce7/ffffff?text=3D+Vision+System'>"
collection: portfolio
---

## Industrial 3D Inspection Pipeline

**Organization:** CSIR-National Aerospace Laboratories  
**Focus:** Point cloud processing for defect detection

### Overview
Complete 3D vision system for industrial inspection, combining multiple advanced algorithms to achieve 95.8% depth estimation accuracy on complex curved surfaces.

### Technical Approach

**Point Cloud Processing**
- Open3D for 3D data manipulation
- RANSAC for robust plane fitting
- DBSCAN for clustering and outlier detection
- ICP for point cloud registration

**Depth Estimation**
- PCA-based geometric analysis
- Detects defects from **0.01mm to 6.35mm**
- Quadratic surface fitting for curved geometries
- KDTree spatial indexing for optimization

**Anomaly Detection**
- Supervised: PointNet/PointNet++ (100% accuracy)
- Unsupervised: DBSCAN-based clustering
- Geometric feature extraction
- Real-time processing pipeline

### Performance Results

| Method | Accuracy | Use Case |
|--------|----------|----------|
| PointNet (3D) | **100%** | Geometric defects |
| Depth Estimation | **95.8%** | Dent measurement |
| Curved Surface | **85.71%** | Complex geometries |
| KDTree Spatial | **87%** | Surface irregularities |

### Key Achievements

✅ Detects defects invisible to 2D methods  
✅ Sub-100ms processing per scan  
✅ Handles curved and complex surfaces  
✅ Precision down to 0.01mm

### Technologies

`Python` `Open3D` `PointNet` `PointNet++` `NumPy` `RANSAC` `DBSCAN` `ICP` `KDTree` `PyTorch`

### Applications

- Aircraft surface inspection
- Industrial quality control
- Automated NDT (Non-Destructive Testing)
- Robotic vision systems

### Research Contribution

Methods and results contributed to research paper on automated surface damage detection (under review).

---

**Status:** Integrated with multi-modal detection system
