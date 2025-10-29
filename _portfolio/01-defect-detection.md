---
title: "Multi-Modal AI Defect Detection System"
excerpt: "Hybrid YOLOv8 + PointNet achieving 100% accuracy for aerospace applications<br/><img src='https://via.placeholder.com/600x300/1a1a2e/ffffff?text=Defect+Detection+System'>"
collection: portfolio
---

## Aerospace Defect Detection with 100% Accuracy

**Organization:** CSIR-National Aerospace Laboratories  
**Duration:** Aug 2024 - Present  
**Role:** Lead ML Engineer

### Overview
Revolutionary hybrid pipeline combining 2D computer vision (YOLOv8) and 3D point cloud analysis (PointNet) for aerospace defect detection, achieving unprecedented 100% accuracy on industrial datasets.

### Technical Highlights

**Architecture**
- Dual-model system: YOLOv8 (88.57% on 2D) + PointNet (100% on 3D)
- Custom cross-model NMS eliminating false positives
- Real-time processing pipeline with sub-100ms latency

**Dataset & Processing**
- 10,000+ annotated images
- 1,000+ 3D point clouds
- Automated annotation workflow (70% time reduction)
- Advanced augmentation (55 → 518 samples)

**Key Innovations**
1. **Cross-Modal Fusion**: Combining 2D and 3D for robust detection
2. **PCA-based Depth Estimation**: 0.01mm to 6.35mm defect detection
3. **Curved Surface Analysis**: 85.71% accuracy on complex geometries
4. **KDTree Spatial Indexing**: 87% accuracy improvement

### Performance Metrics

| Metric | Result |
|--------|--------|
| 3D Detection Accuracy | **100%** |
| 2D Detection Accuracy | 88.57% |
| Depth Estimation | 88.8% |
| Inference Speed | 30 FPS |
| Latency | <100ms |
| Precision Improvement | +35% |

### Technologies Used

`Python` `PyTorch` `YOLOv8` `PointNet` `Open3D` `RANSAC` `DBSCAN` `OpenCV` `Raspberry Pi` `Streamlit` `PyQt5`

### Deployment

✅ Real-time system on Raspberry Pi  
✅ Web interface with live camera integration  
✅ Desktop application for offline analysis  
✅ Robotic system integration

### Research Publication

Paper on automated surface damage detection currently **under review** at a leading journal.

---

**Status:** Production deployment at CSIR-NAL
