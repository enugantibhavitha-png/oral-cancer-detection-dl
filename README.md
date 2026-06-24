# Oral Cancer Detection Using Deep Learning

## Overview
This research project develops a hybrid deep learning framework 
for early-stage oral cancer detection from clinical images. 
The system integrates multiple deep learning architectures — 
RNN, LSTM, GRU, GAN, and Autoencoders — with traditional 
machine learning techniques to improve accuracy and robustness 
in distinguishing between cancerous and non-cancerous oral tissue.

The framework addresses a critical global health challenge: 
oral cancer accounts for approximately 53,000 cases per year 
in the United States alone, and despite advances in treatment, 
overall mortality from Oral Cavity Squamous Cell Carcinoma 
(OCSCC) has not decreased significantly since the 1980s — 
primarily due to late-stage diagnosis.

> 📄 **Published Project Report — Panimalar Engineering College, 2024**
> Bachelor of Engineering in Electronics & Instrumentation Engineering
> Affiliated to Anna University, Chennai

---

## Authors
- **Bhavitha Enuganti**
- Akshaya B.C 
- Sangeetha R

**Internal Guide:** Mr. V. Vasudhevan M.E., Assistant Professor,
Department of ECE, Panimalar Engineering College

---

## Problem Statement
Existing oral cancer detection systems face critical limitations:
- Traditional methods rely solely on clinical data or image 
  analysis — leading to suboptimal performance
- Existing systems struggle with feature representation and 
  integration across diverse oral cancer manifestations
- Invasive oral biopsies were required for early-stage OCSCC 
  diagnosis — time-consuming and not accessible in primary care 
  or developing countries
- Limited use of deep learning for comprehensive multi-modal 
  feature extraction and classification

---

## Proposed System — Hybrid Deep Learning Framework

### Architecture Overview
The proposed system introduces a multi-architecture hybrid 
deep learning framework that combines:

| Architecture | Role |
|---|---|
| RNN (Recurrent Neural Network) | Sequential image feature extraction |
| LSTM (Long Short-Term Memory) | Capturing long-range dependencies in image sequences |
| GRU (Gated Recurrent Unit) | Efficient sequential pattern learning |
| GAN (Generative Adversarial Network) | Data augmentation and synthetic sample generation |
| Autoencoders + VGG16 | Deep feature extraction and dimensionality reduction |
| Traditional ML Classifiers | Final classification and ensemble decision-making |

---

## Methodology

### Phase 1 — Data Collection & Preprocessing
- Collected oral cancer image datasets encompassing 
  cancerous and non-cancerous tissue samples
- Applied anisotropic filtering for noise reduction and 
  edge boundary enhancement
- Preprocessed images for consistency in resolution, 
  contrast, and orientation

### Phase 2 — Feature Extraction
- Applied hybrid feature extraction combining CNN-based 
  spatial features with RNN-based sequential features
- Used VGG16 as a pretrained backbone for deep visual 
  feature extraction via transfer learning
- Extracted features capturing texture, shape, edge 
  patterns, and cellular morphology

### Phase 3 — Feature Selection & Optimization
- Applied feature selection to reduce redundant input 
  variables and improve model efficiency
- Used optimization methods to reduce dimensionality 
  while preserving discriminative information

### Phase 4 — Classification
- Deep learning classifier applied for final cancer vs. 
  non-cancer binary classification
- Evaluated across accuracy, sensitivity, and specificity
- Confusion matrix analysis used to assess model performance 
  and identify improvement opportunities

---

## Deep Learning Techniques Used

### CNN Layer Architecture
| Layer | Function |
|---|---|
| Input Layer | Image ingestion and normalization |
| Convolutional Layer | Local feature detection (edges, textures) |
| ReLU Layer | Non-linear activation for feature amplification |
| Max Pooling Layer | Spatial dimensionality reduction |
| Batch Normalization | Training stabilization, faster convergence |
| Fully Connected Layer | Feature combination for final classification |
| SoftMax Layer | Probability output for class prediction |

### Algorithms Used
- **RNN** — Sequential image data feature extraction
- **LSTM** — Long-range dependency modeling
- **GRU** — Efficient sequential feature learning
- **GAN** — Synthetic data generation for class balancing
- **Autoencoder + VGG16** — Deep feature extraction

---

## Software Requirements
| Tool | Version |
|---|---|
| MATLAB | R2021a (Version 9.10) |
| Deep Learning Toolbox | MATLAB built-in |
| Image Processing Toolbox | MATLAB built-in |

---

## Key Research Contributions
- Developed a novel hybrid deep learning framework combining 
  5 neural network architectures for oral cancer detection
- Applied hybrid feature extraction mechanism dynamically 
  extracting features across all oral image types
- Improved detection accuracy over existing single-architecture 
  approaches through multi-model feature fusion
- Addressed research gaps in early-stage OCSCC detection 
  using deep learning neural networks
- Demonstrated potential to replace invasive oral biopsy 
  procedures with non-invasive AI-assisted screening

---

## Results & Evaluation
- Model evaluated on accuracy, sensitivity, and specificity
- Confusion matrix analysis performed across all classification 
  outcomes to identify true/false positive and negative rates
- System demonstrated improved performance over existing 
  SVM and K-means clustering baseline approaches
- Future work: web or app interface for clinical deployment 
  and larger multi-dataset validation

---

## Research Gap Addressed
- Prior research used limited feature sets — reducing accuracy
- Previous methods underutilized deep learning for 
  classification, relying on SVM and K-means clustering
- Insufficient focus on preprocessing in existing approaches
- This work introduces hybrid feature extraction and deep 
  learning classification to address all identified gaps

---

## Applications
- **Early Detection Support** — non-invasive AI screening tool
- **Clinical Decision Making** — supporting clinicians with 
  automated image-based diagnosis
- **Developing Countries** — accessible alternative to 
  invasive biopsy in primary care settings
- **Cost Reduction** — reducing cancer care screening costs 
  through automated early detection

---

## Future Enhancements
- Integrate more comprehensive deep learning architectures 
  for improved classification accuracy
- Develop a web application or mobile app for clinical use 
  by doctors and nurses
- Expand dataset diversity across populations, imaging 
  conditions, and equipment
- Combine multiple datasets from multiple imaging modalities

---

## Skills Demonstrated
- Deep Learning (RNN, LSTM, GRU, GAN, Autoencoders, CNN)
- Transfer Learning (VGG16)
- Medical Image Processing & Computer Vision
- Feature Extraction & Selection
- MATLAB Deep Learning Toolbox
- Healthcare Analytics & Clinical AI
- Research Writing & Academic Publication

---

## Author
**Bhavitha Enuganti**
M.S. Information Systems & Technology — University of North Texas
🔗 [LinkedIn](https://www.linkedin.com/in/bhavitha-enuganti-199195322/)
🐙 [GitHub](https://github.com/enugantibhavitha-png)
🌐 [Portfolio](https://enugantibhavitha-png.github.io)
