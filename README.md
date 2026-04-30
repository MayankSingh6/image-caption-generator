# 🖼️ Image Caption Generator

A local AI-powered image captioning app that generates natural language captions from uploaded images using the **BLIP image-to-text model**.

## 🚀 Overview

This project allows users to upload an image and automatically generate a caption using a locally running computer vision model.

The app is built with:

- Streamlit for the web interface
- Hugging Face Transformers for model loading
- BLIP `Salesforce/blip-image-captioning-base` for image captioning
- PyTorch for model inference

## 🔄 How It Works

1. User uploads an image
2. The image is converted to RGB format
3. BLIP processor prepares the image
4. BLIP model generates a caption
5. Caption is displayed in the Streamlit app

## 🧠 Model Used

Model:

```text
Salesforce/blip-image-captioning-base
Step by step details under Images/ ppt
