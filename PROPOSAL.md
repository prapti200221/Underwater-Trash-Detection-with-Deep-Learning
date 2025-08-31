## Project proposal form

Please provide the information requested in the following form. Try provide concise and informative answers.

**1. What is your project title?** 

Underwater Trash Detection Using Deep Learning  

---

**2. What is the problem that you want to solve?**  

Marine pollution is a critical environmental challenge, with 8 million tons of plastic entering oceans annually (UNEP). Floating and submerged debris cause ecological damage, threaten marine life, and impact human activities (fishing, tourism, etc). Traditional trash detection methods rely on manual divers, sonar scans, and drone surveys, which are expensive, slow, and lack scalability.
**Solution we propose to the problem is an AI underwater detection system that:**
We propose an AI-powered underwater detection system that automatically detects and classifies marine waste in real-time using deep learning. This system may assist cleanup teams and autonomous underwater robots, while handling challenging underwater conditions such as low visibility, turbidity, and lighting variations, making marine debris detection more efficient and scalable. 

---

**3. What deep learning methodologies do you plan to use in your project?**

a. Object Detection (Plastic Classification & Localization):
- YOLOv8 (fast & optimized for real-time applications).
- Faster R-CNN (high accuracy for challenging environments).

b. Feature Extraction (Transfer Learning for Robustness):
- ResNet-50, EfficientNet-B4 (pre-trained on large-scale image datasets to improve generalization).

c. Semantic Segmentation (Precise Garbage Identification):
- U-Net (pixel-wise segmentation for waste boundaries).
- DeepLabV3+ (handles noise & occlusions in underwater imagery).

d. Data Augmentation (Enhancing Model Generalization):
- Simulate real underwater conditions (turbidity, lighting shifts, color distortion).
- Synthetic data generation using GANs (for low-data scenarios).

---

**4. What dataset will you use? Provide information about the dataset, and a URL for the dataset if available. Briefly discuss suitability of the dataset for your problem.** 

This project utilizes the Ocean Waste Detection dataset, which contains over 5,000 annotated underwater images capturing various types of waste materials—such as plastic, metal, and glass - in realistic oceanic environments. The dataset exhibits a wide range of object scales, illumination conditions, and occlusions, making it highly representative of the challenges faced in real-world marine debris detection tasks.
- **Primary Dataset**: [Ocean Waste Detection](https://universe.roboflow.com/object-detect-dmjpt/ocean_waste/dataset/1/download)  
  - The dataset was converted into multiple structural formats to support diverse model architectures: YOLOv8 format for object detection using the YOLO family, TFRecord format for TensorFlow-based detectors like EfficientDet, and binary mask format for semantic segmentation models such as U-Net and its variants.
  - This multi-format preparation allows a unified dataset to be effectively leveraged across various model types (object detectors, segmentation networks, and transformer-based architectures), ensuring a fair and consistent benchmark for model comparison and evaluation. 
 
 
---

**5. List key references (e.g. research papers) that your project will be based on?**
1. [A Robotic Approach towards Quantifying Epipelagic Bound Plastic Using Deep Visual Models](https://arxiv.org/pdf/2105.01882)

---

**Please indicate whether your project proposal is ready for review (Yes/No): YES**

## Feedback (to be provided by the course lecturer)

[MV] 29 March 2025. **Approved**.

The problem concerns an image recognition task involving both classification and localisation. From the proposal, it is unclear whether you intend to focus solely on classification. This problem provides an opportunity to apply and evaluate various deep learning methods for image recognition, such as convolutional neural networks, vision transformers, and those mentioned in the proposal. You may also wish to explore methodologies beyond those covered in class. 
