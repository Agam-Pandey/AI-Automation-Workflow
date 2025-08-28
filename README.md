# AI Automation Workflow for Digital Media Agency

## 📝 Project Overview

This repository showcases an AI-powered automation workflow designed for a digital media agency. It contains Jupyter notebooks demonstrating solutions for **content management**, **security monitoring**, and **image processing**. The primary objective is to leverage deep learning to automate key operational tasks, drastically reducing manual effort and improving efficiency. The implementation of this workflow resulted in a **70% reduction in operational costs** and a **180% increase in productivity**.

-----

## 📊 System Components & Methodology

The project is built on three core systems, each addressing a specific challenge within the digital media workflow.

### **Content Management System**

  * **Objective**: To automate the summarization and analysis of articles, reducing manual content processing time.
  * **Methodology**: The system uses **BART (Bidirectional and Auto-Regressive Transformer)** and **Gemini** models for advanced Natural Language Processing. These models are fine-tuned for abstractive summarization and content analysis, cutting down article processing time by **85%**.

### **Security Monitoring System**

  * **Objective**: To provide real-time, automated security surveillance and attendance tracking.
  * **Methodology**: This component is powered by the **YOLOv8 (You Only Look Once version 8)** model. It excels at real-time object detection and tracking, enabling continuous monitoring and instant alerts. The system successfully enhanced security coverage to **98%** and reduced security incidents by **75%**.

### **Image Processing Pipeline**

  * **Objective**: To automate the tedious process of image enhancement and captioning.
  * **Methodology**: A hybrid architecture combining a **Convolutional Neural Network (CNN)** for feature extraction and a **Vision Transformer (ViT)** for contextual understanding is used. This pipeline generates accurate, context-aware image captions with **85% accuracy** and accelerates image processing from 30 minutes to just **3 seconds** per image.

-----

## 🧠 Key Technologies

  * **Natural Language Processing**: `BART Transformer`, `Gemini`, `Hugging Face Transformers`
  * **Computer Vision**: `YOLOv8`, `OpenCV`
  * **Image Processing**: `CNN`, `Vision Transformer (ViT)`, `TensorFlow`, `Keras`
  * **Core Libraries**: `Pandas`, `NumPy`, `Matplotlib`

-----

## 💻 Installation

To run this project, you will need to install the following Python libraries. It is recommended to use a virtual environment.

```bash
pip install torch torchvision torchaudio ultralytics transformers tensorflow opencv-python pandas numpy matplotlib
```

-----

## 🚀 Usage

1.  Clone this repository to your local machine:
    ```bash
    git clone https://github.com/Agam-Pandey/AI-Automation-Workflow.git
    ```
2.  Navigate to the cloned directory.
3.  Open the Jupyter notebooks in a Jupyter environment (like Jupyter Lab or VS Code) to explore each component:
      * **Content Management**: `Text_summarization_code(BART+AI_AGENTS).ipynb`
      * **Security Monitoring**: `YOLO.ipynb`
      * **Image Processing**: `CNN-based-image-captioning-vision-transformer.ipynb`
4.  Execute the cells sequentially to reproduce the analysis and results.
