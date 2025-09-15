---
type: ProjectLayout
title: Flood Detection System Using Image Segmentation
colors: colors-f
date: '2024-12-01'
client: Personal Project
description: >-
  A real-time water level detection system using YOLOv8n semantic segmentation to automatically detect water areas and measure water levels in images/videos for flood monitoring and early warning systems.
featuredImage:
  type: ImageBlock
  url: /images/projects/water.webp
  altText: AI flood detection system showing water level monitoring interface
media:
  type: VideoBlock
  url: /images/projects/water.mp4
  altText: YOLOv8n model detecting water areas and measuring real-time water levels
  caption: Real-time flood detection system in action - showing water area detection and level measurement
---

## Project Overview

This AI-powered flood detection system leverages computer vision and machine learning to provide real-time water level monitoring. Using a custom-trained YOLOv8n semantic segmentation model, the system can automatically detect water areas in images and videos, then calculate precise water levels using geometric analysis and pixel-to-meter conversion.

## Key Features

- **Real-time Water Detection**: YOLOv8n semantic segmentation for accurate water area identification
- **Water Level Measurement**: Precise calculation using reference lines and pixel-to-meter conversion
- **Interactive GUI**: User-friendly Tkinter interface for easy operation
- **Video Processing**: Real-time processing with output video generation
- **Configurable Parameters**: Customizable warning thresholds and measurement settings
- **Pre-trained Model**: Included `best.pt` model trained on custom dataset

## Technologies Used

- **AI/ML**: YOLOv8n semantic segmentation, Ultralytics
- **Computer Vision**: OpenCV, image processing libraries
- **GUI Development**: Tkinter for user interface
- **Data Processing**: Shapely for geometric calculations
- **Data Labeling**: Roboflow for dataset preparation
- **Version Control**: Git with comprehensive documentation

## Technical Implementation

The system combines multiple technical approaches:

1. **Model Training**: Custom dataset from Kaggle combined with self-labeled data using Roboflow
2. **Water Detection**: YOLOv8n model processes each frame to identify water areas
3. **Level Calculation**: Geometric intersection algorithms calculate water height using reference lines
4. **Real-time Processing**: Live video stream analysis with immediate results
5. **Output Generation**: Processed videos saved locally for analysis

## Challenges & Solutions

The primary challenge was achieving accurate water level measurements from 2D images. I solved this by implementing a reference line system where users provide perpendicular line coordinates, enabling precise pixel-to-meter conversion. The geometric intersection algorithms handle the complex calculations needed for accurate water level determination.

> "The intersection of AI and environmental monitoring creates powerful tools for disaster prevention and public safety."

## Results

- **8 GitHub stars** and active community engagement
- **30 commits** showing consistent development and improvement
- **Real-time processing** capability for live flood monitoring
- **Accurate measurements** using geometric analysis
- **Open-source availability** for community contribution and improvement

## Future Development

Current limitations include single-area detection per frame and intersection calculation challenges with multiple water areas. Future updates will focus on:
- Multi-area water detection capabilities
- Improved intersection algorithms for complex scenarios
- Enhanced accuracy with better reference line selection
- Integration with IoT sensors for automated monitoring

## Repository

**GitHub**: [duchieu260503/Flood-detection](https://github.com/duchieu260503/Flood-detection)
- Complete source code and documentation
- Pre-trained model included
- Setup instructions and requirements
- Example media files for testing
