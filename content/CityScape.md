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

A full-stack AI web application performing real-time semantic segmentation on urban street images .

### Project Overview

Built an end-to-end AI application that performs real-time semantic segmentation on urban street images using **DeepLabV3 + ResNet-50** trained on the Cityscapes dataset with 34 classes. The project combines a high-performance PyTorch backend, a modern React frontend, experiment tracking, and complete containerization.

### Key Achievements

- **Model Performance:** Trained DeepLabV3 + ResNet-50 on the Cityscapes dataset achieving **25.6% mIoU** and **0.308 Dice score** over 20 epochs
- **Backend:** Built a REST API with FastAPI serving real-time segmentation inference with per-class coverage percentages
- **Frontend:** Developed a React + Vite interface with drag-and-drop image upload and live result visualization
- **Experiment Tracking:** Tracked all experiments, metrics, and artifacts using MLflow
- **Deployment:** Containerized the full stack (backend, frontend, MLflow) with Docker Compose

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
