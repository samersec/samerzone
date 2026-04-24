---
title: CityScape — Full-Stack Semantic Segmentation Web App
date: 2025-04-15
tags:
  - project
  - ai
  - deeplearning
  - pytorch
  - fastapi
  - react
  - docker
---

## CityScape — Full-Stack Semantic Segmentation Web App

A full-stack AI web application performing real-time semantic segmentation on urban street images.

### Project Overview

Built an end-to-end AI application that performs real-time semantic segmentation on urban street images using **DeepLabV3 + ResNet-50** trained on the Cityscapes dataset with 34 semantic classes. The project combines a high-performance PyTorch backend, a modern React frontend, experiment tracking, and complete containerization.

### Key Achievements

- **Model:** DeepLabV3 + ResNet-50 trained on the Cityscapes dataset (34 classes)
- **Backend:** Real-time semantic segmentation REST API with FastAPI serving per-class coverage percentages
- **Frontend:** React + Vite interface with drag-and-drop image upload and live result visualization
- **Experiment Tracking:** MLflow experiment tracking with full artifact and metrics logging
- **Deployment:** Full Docker containerization with Docker Compose (backend, frontend, MLflow)

### Gallery

![CityScape Demo 1](/static/image1.png)
![CityScape Demo 2](/static/image2.png)
![CityScape Demo 3](/static/image3.png)
![CityScape Demo 4](/static/image4.png)

### Tech Stack

- **Deep Learning:** PyTorch, DeepLabV3, ResNet-50
- **Backend:** Python, FastAPI
- **Frontend:** React, Vite, TypeScript
- **Experiment Tracking:** MLflow
- **Deployment:** Docker, Docker Compose
- **Dataset:** Cityscapes (34 semantic classes)

### What I learned

- End-to-end deep learning pipeline from training to production
- Building scalable REST APIs with FastAPI for ML model serving
- Real-time image processing and visualization in React
- Containerizing complex multi-service applications with Docker Compose
- Organizing ML experiments with MLflow for reproducibility and comparison
- Deploying AI models efficiently with proper API design and performance optimization

### Resources

- **GitHub Repository:** [samersoltanii/cityscapes-deeplab](https://github.com/samersoltanii/cityscapes-deeplab.git)
- **Dataset:** [Cityscapes Image Pairs on Kaggle](https://www.kaggle.com/datasets/dansbecker/cityscapes-image-pairs)
