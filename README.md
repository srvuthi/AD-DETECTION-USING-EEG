# Fine-Tuned CEEDNet for Alzheimer's Detection using EEG

This repository contains a fine-tuned version of the **CEEDNet** model from Chung-Ahn University (original repo), designed to **improve detection specificity for Alzheimer's Disease (AD)** using EEG data.

<img width="949" height="542" alt="image" src="https://github.com/user-attachments/assets/1add78d9-9eb0-4537-ac7a-16fe5e5293ae" />


---

### 🧠 Overview

The original CEEDNet model uses a **ResNet-18 backbone** and was trained to detect general dementia, achieving an accuracy of **68.75%**.

In this project, we fine-tuned the model **specifically for Alzheimer's Disease**, improving the model's performance to **77% accuracy**.

The preprocessing steps for the data used to finetune are as follows:
<img width="1236" height="252" alt="image" src="https://github.com/user-attachments/assets/ef53e679-be1d-4da2-94df-1ca59d16cba8" />

---

### 🚀 How to Use

#### 1. Clone the Original CEEDNet Repository

```bash
git clone https://github.com/ipis-mjkim/caueeg-ceednet
cd caueeg-ceednet
```

#### 2. Run the Training Notebook:
Open train.ipynb and run all cells to train the fine-tuned model. This will save a model checkpoint after training.

#### 3. Run Inference:
After training, use the provided inference script or notebook to evaluate the fine-tuned model on test data.
