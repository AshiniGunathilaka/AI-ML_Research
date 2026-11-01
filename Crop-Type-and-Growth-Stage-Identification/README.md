#  Image-Based Crop Type and Growth Stage Identification Using Deep Learning for Agricultural Monitoring

**An Academic Research Project | Artificial Intelligence & Computer Vision**

## Research Overview

Agriculture plays a vital role in Sri Lanka's economy and food security. However, monitoring crop development, particularly during early growth stages, can be challenging for farmers who often rely on manual observation and experience.

This research investigates the use of **Deep Learning and Computer Vision** to automatically identify crop types and early plant growth stages from images. The study explores how image-based AI techniques could contribute to more efficient agricultural monitoring and support informed farm management decisions.

The research focuses on the potential of an integrated image-classification approach that can identify both *what crop is growing* and *which early growth stage it has reached*.

## Research Information

| Detail | Description |
|---|---|
| Researcher | M.D.A.S Gunathilaka |
| Academic Supervisor | Professor M.Ichikawa |
| Research Area | Artificial Intelligence and Deep Learning |
| Application Domain | Agricultural Monitoring |
| Main Approach | Image-Based Multi-Task Classification |
| Model Architecture | MobileNetV2 |
| Research Type | Academic Research |

## Research Objectives

- Investigate the application of deep learning in agricultural image analysis.
- Develop an image-based approach to identify different crop types.
- Explore the classification of early plant growth stages.
- Evaluate whether a single CNN-based model can perform both classification tasks.
- Examine the impact of image preprocessing and data augmentation on model performance.
- Explore the potential of AI-based approaches to support agricultural monitoring, particularly in Sri Lankan farming contexts.

## Research Methodology

The study followed an experimental research approach supported by a review of existing literature on agricultural monitoring, deep learning, and computer vision.

The experimental work included:

**1. Dataset Development**

A synthetic image dataset was developed using AI-generated plant images. It contained 10,000 images representing five crop types and ten early growth stages.

**2. Image Preprocessing**

Images were resized to 224 × 224 pixels and normalized before being used for model training.

**3. Data Augmentation**

Limited brightness and zoom variations were applied to introduce image variability while maintaining the visual characteristics of plant development.

**4. Deep Learning Model**

A CNN-based architecture using MobileNetV2 and transfer learning was explored. A shared feature extraction network was used with two classification outputs:

- Crop Type Classification
- Growth Stage Classification

**5. Model Evaluation**

The model was evaluated using accuracy, precision, recall, F1-score, and confusion matrix analysis.

## Experimental Results

The research demonstrated the potential of using a CNN-based approach to identify crop types and early plant growth stages from images.

| Evaluation Area | Result |
|---|---:|
| Crop Classification Accuracy | 73% |
| Growth Stage Classification Accuracy | Approximately 69% |
| Training Accuracy | 73% |
| Validation Accuracy | 69% |

The experiments also showed that limited data augmentation improved classification performance compared with the experiments conducted without augmentation.

The findings highlighted that visually similar crops and neighbouring growth stages can be difficult to distinguish, particularly during early plant development.

## Key Research Contributions

- Explored a combined approach to crop type and early growth stage identification.
- Investigated the use of MobileNetV2 for agricultural image classification.
- Developed a structured synthetic dataset covering five crop types and ten early growth stages.
- Evaluated the influence of image augmentation on model performance.
- Identified challenges associated with visually similar crop types and gradual plant development.
- Examined the potential of image-based AI approaches for agricultural monitoring in Sri Lanka.

## Research Limitations and Future Directions

The study used synthetic images rather than images collected directly from real agricultural fields. Therefore, the experimental results represent a proof of concept and do not establish real-world field performance.

Future research could explore:

- Training and validation using real agricultural field images.
- Combining synthetic and real-world image datasets.
- Investigating advanced architectures such as EfficientNet and Vision Transformers.
- Expanding the range of crop types and growth stages.
- Exploring the integration of environmental data with image-based analysis.
- Evaluating the approach in practical agricultural environments.

## Research Significance

This research contributes to the exploration of Artificial Intelligence and Computer Vision in agriculture. By investigating the identification of both crop types and early growth stages, the study explores an approach that could eventually support more consistent crop monitoring and agricultural decision-making.

The research is particularly relevant to the development of accessible AI-based agricultural solutions that could benefit smallholder farmers, agricultural researchers, extension officers, and institutions involved in agricultural planning.

## Technologies and Research Areas

- Python
- TensorFlow and Keras
- MobileNetV2
- Convolutional Neural Networks (CNN)
- Deep Learning
- Computer Vision
- Image Classification
- Transfer Learning
- Image Preprocessing and Data Augmentation

---

*This repository presents an overview of the research, methodology, and experimental findings. Research source code, datasets, and other academic materials are not included in this public portfolio.*

**Researcher:** M.D.A. Shehara Gunathilaka  
**Supervisor:** Professor M.Ichikawa
