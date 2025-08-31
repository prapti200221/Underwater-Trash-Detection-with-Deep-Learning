# 🌊 Comparative Analysis of Different Underwater Trash Detection Models 🐠

## 📖 Overview

Marine pollution is a critical environmental challenge, with 8 million tons of plastic entering oceans annually (UNEP). Floating and submerged debris cause ecological damage, threaten marine life, and impact human activities such as fishing and tourism. Traditional trash detection methods rely on manual divers, sonar scans, and drone surveys, which are expensive, slow, and lack scalability.

This project proposes analyses deep learning-based framework for underwater detection tasks that automatically detect and classify marine waste. These systems aim to assist cleanup teams and autonomous underwater robots while handling challenging underwater conditions such as low visibility, turbidity, and lighting variations, making marine debris detection more efficient and scalable.

---

## 🎯 Objectives

1. Test and analyse the performance of different neural network architectures for object detection and semantic segmentation.
2. Provide a scalable and efficient solution for real-time marine debris detection.

---

## 📂 Dataset

The project utilizes the **Ocean Waste Detection** dataset, which contains over 5,000 annotated underwater images capturing various types of waste materials—such as plastic, metal, and glass—in realistic oceanic environments. The dataset has been converted into multiple structural formats to support diverse model architectures:
- **YOLOv8 format** for object detection using the YOLO family.
- **TFRecord format** for TensorFlow-based detectors like EfficientDet.
- **Binary mask format** for semantic segmentation models such as U-Net and its variants.

This multi-format preparation ensures a fair and consistent benchmark for model comparison and evaluation. 

---

## 🛠️ Methodology

### Neural Network Architectures
The project explores the following deep learning architectures:
- **YOLOv8** for object detection. 
- **EfficientDet** for object detection using TensorFlow. 
- **U-Net with VGG, ResNet, and ConvNeXt backbones** for semantic segmentation. 

### Training Methods
- Optimizers: Adam, SGD
- Learning rate scheduling 
- Techniques to mitigate overfitting: dropout, data augmentation, and early stopping

### Evaluation Metrics
- Mean Average Precision (mAP) for object detection
- Intersection over Union (IoU) for segmentation tasks
- Precision, recall, and F1-score for classification accuracy

---

## 📊 Results and Discussion

The results of the experiments will be presented in the final report, including:
1. Numerical evaluation results with detailed discussions.
2. Comparison of different architectures and their performance under varying underwater conditions.
3. Conclusion and insights gained from different models' behaviour.



---

## 🙏 Acknowledgments

This project is part of the ST456 course at LSE (WT 2025). We thank the course lecturers and teaching assistants for their guidance and support. 💡
