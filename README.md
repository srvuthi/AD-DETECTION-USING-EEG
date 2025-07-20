# Fine-Tuned CEEDNet for Alzheimer's Detection using EEG

This repository contains a fine-tuned version of the **CEEDNet** model from Chung-Ahn University (original repo), designed to **improve detection specificity for Alzheimer's Disease (AD)** using EEG data.

<img width="561" height="358" alt="Architec drawio" src="https://github.com/user-attachments/assets/73158874-3705-4a24-b269-43c96c28a02b" />

---

### 🧠 Overview

The original CEEDNet model uses a **ResNet-18 backbone** and was trained to detect general dementia, achieving an accuracy of **68.75%**.

In this project, we fine-tuned the model **specifically for Alzheimer's Disease**, improving the model's performance to **77% accuracy**.

The preprocessing steps for the data used to finetune are as follows:
<img width="901" height="139" alt="PreProcessing drawio (1)" src="https://github.com/user-attachments/assets/4754a1e7-4342-4369-9ce1-4c1214fcc8c9" />

---

### 🚀 How to Use

#### 1. Clone the Original CEEDNet Repository

```bash
git clone https://github.com/ipis-mjkim/caueeg-ceednet
cd caueeg-ceednet

Run the Training Notebook:
Open train.ipynb and run all cells to train the fine-tuned model. This will save a model checkpoint after training.

Run Inference:
After training, use the provided inference script or notebook to evaluate the fine-tuned model on test data.
