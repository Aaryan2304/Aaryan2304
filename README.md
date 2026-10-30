<div align="center">

# Aaryan Kurade

### Computer Vision & Perception Engineer

Building practical ML systems for **2D/3D vision, robotics perception, and geospatial imagery**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aaryan-kurade)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-2563EB?style=flat&logo=googlechrome&logoColor=white)](https://aaryan2304.github.io/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:aaryankurade27@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Aaryan2304-181717?style=flat&logo=github&logoColor=white)](https://github.com/Aaryan2304)

</div>

---

## About

I am a Computer Vision / Machine Learning Engineer with a B.Tech in Electronics and Communication Engineering (AI/ML) from MIT World Peace University, Pune.

My work focuses on building end-to-end vision pipelines, from data preparation and model development to inference, geometric processing, and application integration. My experience covers **object detection, instance segmentation, tracking, OCR, pose estimation, RGB-D perception, and geospatial computer vision**.

I have worked on industrial inspection and robotics-perception workflows, and I am currently building deeper expertise in **SAR imagery, remote sensing, and satellite-image analysis**. I am interested in problems where computer vision supports robotics, autonomous systems, aerospace/space applications, and other real-world perception systems.

## Focus Areas

- **2D Computer Vision:** Object detection, instance segmentation, multi-object tracking, OCR, and pose estimation.
- **3D & Robotics Perception:** RGB-D point clouds, 6-DoF pose estimation, CAD/STL matching, coordinate transformations, and yaw-pitch-roll calculations.
- **Geospatial AI & Remote Sensing:** SAR/EO imagery, GeoTIFF processing, oriented bounding boxes (OBB), georeferenced detection, and cross-domain evaluation.
- **ML Systems:** PyTorch inference pipelines, ONNX export, quantization, FastAPI services, Docker, and concurrent processing.

## Selected Projects

### 1. [SAR Ship Detection Pipeline](https://github.com/Aaryan2304/sar-ship-detection-pipeline)

An end-to-end SAR ship-detection workflow with oriented bounding boxes and cross-domain evaluation.

- Processes large GeoTIFF imagery into tiles and converts SSDD rotated-box annotations to YOLO OBB format.
- Trains a YOLO26s-OBB detector on SSDD and evaluates transfer to independent Umbra X-band SAR chips.
- Includes SAR-aware augmentation, annotation checks, dataset quality control with FiftyOne, and per-chip percentile-normalization experiments.
- **SSDD baseline:** 0.9868 mAP@50 and 0.7957 mAP@50:95. Cross-domain evaluation is used to study sensor and intensity-distribution shift.

**Tools:** `Python` `YOLO26-OBB` `Rasterio` `GeoTIFF` `FiftyOne` `OpenCV`

### 2. [SAR2EO — SAR-to-EO Image Translation](https://github.com/Aaryan2304/sar2eo-pix2pix)

A paired image-to-image translation project that maps Sentinel-1 SAR VV patches to Sentinel-2 optical RGB patches using Pix2Pix.

- Implements a U-Net generator and PatchGAN discriminator using PyTorch.
- Uses the SEN1-2 paired dataset, with train/validation/test splits organised by terrain class.
- Compares an L1-only baseline with the full adversarial model.
- Evaluates perceptual and structural quality with LPIPS, FID, SSIM, and PSNR. The adversarial model improves LPIPS/FID while the L1-only baseline performs better on SSIM/PSNR.

**Tools:** `PyTorch` `Pix2Pix` `Conditional GANs` `Sentinel-1` `Sentinel-2` `LPIPS` `FID`

### 3. [Sports Computer Vision Analytics](https://github.com/Aaryan2304/sports-ai) · [SportsVision+](https://github.com/Aaryan2304/sportsvision-plus)

A collection of sports-focused CV projects for video analysis and tactical visualisation.

- Covers workflows for player and ball detection, multi-object tracking, and team classification.
- Explores court/pitch mapping with homography, player positioning, and visual analytics.
- Includes volleyball and football work, with the repositories documenting the status and scope of each module.

**Tools:** `YOLO` `RT-DETR` `ByteTrack` `Supervision` `OpenCV` `Homography` `scikit-learn`

### 4. [AI-Powered Visual Search Engine](https://github.com/Aaryan2304/visual-search-engine)

An image-retrieval system for fashion images using visual embeddings and vector similarity search.

- Generates image embeddings with CLIP and indexes them in FAISS.
- Provides a FastAPI backend and Streamlit interface for image-based retrieval.
- Includes a modular processing pipeline, local persistent indexing, tests, and Docker configuration.

**Tools:** `PyTorch` `CLIP` `FAISS` `FastAPI` `Streamlit` `Docker`

## Technical Stack

| Area | Technologies & Methods |
|---|---|
| **Languages** | Python |
| **ML & Deep Learning** | PyTorch, TensorFlow, NumPy, scikit-learn |
| **Computer Vision** | OpenCV, Ultralytics YOLO, RT-DETR, Detectron2, Mask R-CNN, U-Net, PaddleOCR, MediaPipe |
| **Tracking & Video** | ByteTrack, DeepSORT, Supervision, video processing pipelines |
| **3D & Geometry** | RGB-D, point clouds, 6-DoF pose estimation, CAD/STL matching, coordinate transforms, homography |
| **Geospatial** | Rasterio, GDAL, QGIS, GeoTIFF, SAR/EO imagery, OBB workflows |
| **Inference & Backend** | ONNX, model quantization, FastAPI, Docker, multithreading, concurrent inference |

## Experience

### IRDPL — Machine Learning Engineer

**Computer Vision & Robotics Perception**

- Developed vision-side components for an industrial robotics/perception workflow.
- Worked on YOLO-based detection, multithreaded worker pipelines, CAD/STL matching, and orientation calculations (yaw, pitch, and roll).

### Arakoo.ai — Software Engineer Intern

**Speech Processing**

- Contributed to Python-based speech-processing services, including automatic speech recognition and speaker-diarization workflows.

### Utopia Optovision Pvt. Ltd. — Machine Learning Intern

**Industrial Computer Vision**

- Worked on an industrial inspection pipeline combining YOLO-based detection with PaddleOCR.
- Contributed to detection/OCR integration and inference optimisation, including ONNX export.

## Education

**MIT World Peace University, Pune**  
B.Tech — Electronics and Communication Engineering (AI/ML)  
2021–2025

## Areas of Interest

Computer Vision Engineering · ML Engineering · Robotics Perception · Autonomous Systems · Geospatial AI · Remote Sensing · Aerospace & Space Applications

I am open to opportunities where I can build and improve practical computer-vision and perception systems.

---

<div align="center">

### Let's Connect

[LinkedIn](https://www.linkedin.com/in/aaryan-kurade) · [Portfolio](https://aaryan2304.github.io/) · [Email](mailto:aaryankurade27@gmail.com)

<sub>Interested in computer vision, robotics perception, and geospatial AI.</sub>

</div>
