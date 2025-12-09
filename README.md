# AAI521-Group6-ComputerVision-Project


# 🫁 Chest X-Ray Lung Segmentation & Classification

### *AAI521 – Computer Vision Project (Group 6)*

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Build](https://img.shields.io/badge/Build-Passing-brightgreen.svg)]()
[![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange.svg)]()

## 📌 Overview
This project focuses on **lung segmentation and classification** from chest X-ray images using deep learning. The implementation includes data preprocessing, model training, evaluation, and visualization pipelines.

**Dataset:** [Chest X-Ray Masks and Labels](https://www.kaggle.com/datasets/nikhilpandey360/chest-xray-masks-and-labels)

---

## 🚀 Badges

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Build](https://img.shields.io/badge/Build-Passing-brightgreen.svg)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

---

## 👥 Team Members (Group 6)

### **Malla Manu**
- Project identification
- Exploratory Data Analysis
- Data Preprocessing
- Project Documentation for the above tasks
- Conclusions and Report

### **Anugrah Rastogi**
- Project identification
- EDA and Data preprocessing review
- Developing Deep learning models - U‑Net
- Project Documentation for modelling
- Conclusions and Report

### **Ved Prakash Dwivedi**
- Project identification and task planning
- Identifying Exploratory Data Analysis and Data preprocessing
- Experiment with alternative models - ResNet
- Project documentation, presentation and final project video presentation
- Git Merges
- Conclusions and Report

---

## 📅 Project Timeline

| Module | Deadline | Task |
|--------|----------|------|
| Module 1 | Day 7 | Complete Teammate Survey for group preferences |
| Module 2 | - | Assigned to groups of 2-3 members<br>- Connect via Canvas/Email/Slack<br>- Research and propose dataset and project ideas |
| Module 4 | - | Submit Team Project Status Update Form<br>- Finalize dataset selection |
| Module 7 | - | Final project submission (3 deliverables) |
| Module 7 | - | Complete Peer Review for each team member |

## 📋 Evaluation Criteria

### Final Grade Distribution
- **Final Report**: 40%
- **Code Repository**: 30%
- **Presentation**: 30%

### 1. Final Report (40%)
| Criteria | Meets/Exceeds Expectations | Approaches Expectations | Below Expectations |
|----------|---------------------------|------------------------|-------------------|
| **Project Setup** | Clear objectives, feasible approach, proper scoping | Defined but lacks clarity | Questionable feasibility |
| **Modeling Methods** | Well-documented algorithms, clear theory, clean code | Some gaps in documentation | Significant flaws in code/theory |
| **Validation & Metrics** | Thorough validation, relevant metrics | Basic validation, metrics need refinement | Basic or inappropriate metrics |
| **Analysis & Results** | Insightful, well-supported conclusions | Some flaws in presentation | Significant issues with results |
| **Formatting** | APA 7th edition, professional quality | Minor formatting issues | Significant formatting problems |

### 2. Code Repository (30%)
| Criteria | Meets/Exceeds Expectations | Approaches Expectations | Below Expectations |
|----------|---------------------------|------------------------|-------------------|
| **Code Quality** | Well-documented, PEP 8 compliant | Some documentation gaps | Poorly documented |
| **Functionality** | Executes correctly on sample data | Minor execution issues | Significant functional problems |
| **Teamwork** | Clear version control history | Some collaboration evident | Limited team contribution |
| **Documentation** | Comprehensive README | Basic README | Missing or minimal README |

### 3. Presentation (30%)
| Criteria | Meets/Exceeds Expectations | Approaches Expectations | Below Expectations |
|----------|---------------------------|------------------------|-------------------|
| **Content** | Clear, concise, covers all key points | Missing some elements | Significant content gaps |
| **Delivery** | Professional, well-rehearsed | Some presentation issues | Poor delivery quality |
| **Team Participation** | Equal participation from all members | Uneven participation | Minimal team collaboration |
| **Technical Quality** | High-quality audio/video | Minor technical issues | Significant AV problems |

## 📦 Project Deliverables

### 1. Final Report
- **Format**: Single PDF document (7-10 pages + cover, references, and appendix)
- **Contents**:
  - Project methodology and implementation details
  - Analysis of results and findings
  - Appendix with supporting materials
- **Style**: APA 7th edition format

### 2. Code Repository
- **Platform**: GitHub
- **Requirements**:
  - Well-documented code following PEP 8 style guide
  - Comprehensive README
  - Version control history
  - Optional: Interactive web application (Streamlit/Dash)

### 3. Presentation
- **Format**: 10-12 minute recorded video with slides
- **Content**:
  - Project overview and objectives
  - Methodology and implementation
  - Results and findings
  - Team contributions
- **Requirements**:
  - Equal participation from all team members
  - Clear audio and video quality
  - Professional slide deck

## 🎯 Project Objectives

- Develop a robust preprocessing pipeline for chest X-ray images
- Implement and train deep learning models (U-Net, etc.) for accurate lung segmentation
- Evaluate model performance using metrics like Dice coefficient and IoU
- Create a modular and well-documented codebase for medical image analysis
- Enable easy extension for classification or pathology detection tasks

## 📊 Dataset

### **Dataset Details**
- **Source:** [Chest X-Ray Masks and Labels](https://www.kaggle.com/datasets/nikhilpandey360/chest-xray-masks-and-labels) on Kaggle
- **Images:** High-resolution chest X-rays in `.png`/`.jpg` format
- **Annotations:** Binary lung segmentation masks
- **Labels:** Normal/Abnormal classification

### **Dataset Statistics**
| Category | Count |
|----------|-------|
| Annotated Images | 704 |
| Unmasked Images | 192 |
| Total Images | 896 |
| Average Resolution | 1024–3000 px |
| File Size | ~7.5 GB |

### **Directory Structure**
```
data/
├── images/        # Original X-ray images
├── masks/         # Corresponding segmentation masks
└── metadata/      # Additional dataset information
```

## 🛠️ Project Structure

```
AAI521-Group6-ComputerVision-Project/
│
├── 01.Data/                    # Dataset information and documentation
│   └── Readme.md              # Dataset details and structure
│
├── 02_Data_Preprocessing_EDA/  # Data exploration and preprocessing
│   └── EDA_and_Preprocessing.ipynb  # Jupyter notebook for EDA
│
├── 03_Model_Development/       # Model implementation and training
│   ├── Resnet_Model_Development.ipynb  # ResNet model implementation
│   └── Unet_Model_Development.ipynb    # U-Net model implementation
│
└── README.md                  # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- CUDA-compatible GPU (recommended)
- [Conda](https://conda.io/) (recommended)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AAI521-Group6-ComputerVision-Project.git
   cd AAI521-Group6-ComputerVision-Project
   ```

2. Create and activate a conda environment:
   ```bash
   conda create -n lung-seg python=3.8
   conda activate lung-seg
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/nikhilpandey360/chest-xray-masks-and-labels) and extract it into the `data/` directory.

### Usage

1. **Data Exploration**
   ```bash
   jupyter notebook notebooks/01_exploration.ipynb
   ```

2. **Preprocessing**
   ```bash
   jupyter notebook notebooks/02_preprocessing.ipynb
   ```

3. **Model Training**
   ```bash
   jupyter notebook notebooks/03_training.ipynb
   ```

4. **Evaluation**
   ```bash
   jupyter notebook notebooks/04_evaluation.ipynb
   ```


## 📚 References

1. [Chest X-Ray Masks and Labels Dataset](https://www.kaggle.com/datasets/nikhilpandey360/chest-xray-masks-and-labels)
2. Ronneberger, O., Fischer, P., & Brox, T. (2015). [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
3. Recent advances in medical image segmentation (survey papers)

## 🤝 Contributing

We welcome contributions! Please feel free to submit issues and pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

- **Ved Prakash Dwivedi**
- **Anugrah Rastogi**
- **Malla Manu**

## 🙏 Acknowledgments

- Kaggle for hosting the dataset
- Original dataset authors for providing the annotations
- Open-source community for the tools and libraries used in this project
