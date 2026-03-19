# 🚀 AI School Projects Archive

This repository is an archive of the Machine Learning and Deep Learning projects completed by Subin Hyun during the AI Vacation School (AISS, AIWS) programs. It showcases the application of various AI techniques—ranging from Natural Language Processing (NLP) and Computer Vision (CV) to Time-Series Analysis—to solve real-world problems, with a strong focus on Bioinformatics and Computational Biology.

---

## 📁 Projects Overview

### [[2025 AISS](../showcases/2025_aiss.md)] **LLM-Based Toxicity Prediction for Drug Discovery with SMILES and ChemBERTa**
- **Period:** 2025 Jul ~ Aug (AI Summer School)
- **Domain:** Biochemistry / Organic Chemistry / LLM / NLP / Drug Discovery
- **Description:** This project builds a toxicity prediction model for small molecules using the ClinTox dataset (FDA-approved and failed drugs). By extracting tokenized features from SMILES strings using a pre-trained chemical language model (ChemBERTa), the project evaluates the predictive power of Large Language Models in the drug discovery pipeline compared to traditional descriptors (like Morgan Fingerprints, molecular weights, and logP).
- **Tech Stack:** Python, ChemBERTa, Random Forest, RDKit, SMILES Tokenizer
- **Key Results:**
  - Achieved an **Accuracy of 0.9328** and an **F1-Score of 0.9037** when combining ChemBERTa tokenized features with RDKit 20 descriptors.
  - Demonstrated that Multi-Task Learning (MTL) outperformed Single-Task Learning (STL) across all metrics on the Tox21 dataset by effectively mitigating the class imbalance problem.
- 🔗 [Go to Project Directory](./2025_AISS_Clintox_Chemberta)

### [[2025 AIWS](../showcases/2025_aiws.md)] **AI-powered Quality Control in Bioprocessing**
- **Period:** 2025 Jan ~ Feb (AI Winter School)
- **Domain:** Computer Vision / Bioprocessing / Quality Control
- **Description:** An automated Quality Control (QC) system designed to detect and count microbial colonies (such as *E. coli, S. aureus, P. aeruginosa, C. albicans, B. subtilis*) on Petri dishes. The project aims to reduce human error and time costs in pharmaceutical bioprocessing by replacing manual counting with real-time object detection models. 
- **Tech Stack:** Python, YOLOv8n, PyTorch, OpenCV, Object Detection
- **Key Results:**
  - Fine-tuned the YOLOv8n model, achieving an **F1 Score of 0.738** (Precision: 0.955, Recall: 0.602) at 200 epochs.
  - Successfully applied data augmentation techniques (brightness adjustments) to improve model robustness, yielding an improved augmented **F1 Score of 0.741**.
- 🔗 [Go to Project Directory](./2025_AIWS_AI_QC)

### [[2024 AISS](../showcases/2024_aiss.md)] **Harmful Brain Activity Classification**
- **Period:** 2024 Jul ~ Aug (AI Summer School)
- **Domain:** Biosignal Processing / Time-Series Analysis / Computer Vision
- **Description:** A predictive modeling project that classifies harmful brain activity patterns (Seizure, LPD, GPD, LRDA, GRDA, and Others) to assist in the early diagnosis of cerebral diseases. The pipeline converts multi-channel raw EEG signals (.parquet files) into 2D spectrograms using STFT, and extracts feature patterns using a custom Convolutional Neural Network (CNN).
- **Tech Stack:** Python, PyTorch, Pandas, NumPy, 2D CNN, Spectrograms
- **Key Results:**
  - Designed and trained a custom 2D CNN architecture (Conv2D -> MaxPool2D -> Linear layers) on spectrogram image data.
  - Achieved a **Kullback-Leibler (KL) Divergence Loss of 0.3600** on the Kaggle competition evaluation metric using a non-shuffled training approach.
- 🔗 [Go to Project Directory](./2024_AISS_Harmful_Brain_Activity)

## 📎 Side Studies
Besides the main self-study project and the poster presentation, paper-review sessions and AI basic concept lectures were conducted.

### Alphafold paper review
🔗 [Direct link](./Alphafold.pptx)
