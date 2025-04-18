# 📷 Camera Classifier

A machine learning-based Camera Classifier designed to identify and categorize images based on the type or source of the capturing device. This system can distinguish between various camera types (e.g., DSLR, mirrorless, smartphone, webcam) or specific models (e.g., Canon, Nikon, iPhone).

---

## 🚀 Features

- Classifies images based on camera type or model
- Can analyze both image content and metadata (EXIF)
- Useful for digital forensics, image quality analytics, and device usage tracking
- Scalable to add more classes/devices

---

## 🧠 How It Works

1. **Data Collection**: Images are gathered from multiple sources and labeled by camera type or model.
2. **Preprocessing**: Image resizing, normalization, and optional EXIF extraction.
3. **Model Training**: A CNN (or other model) is trained to classify images based on visual features and/or metadata.
4. **Evaluation**: Accuracy and performance metrics are tracked to assess the classifier.
5. **Deployment**: Easily integrate the model into your application or run it as
