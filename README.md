This repository contains a fine-tuned version of the CEEDNet model from Chung-Ahn University (original repo), designed to improve detection specificity for Alzheimer's Disease (AD) using EEG data.

OVERVIEW
The original CEEDNet model utilizes a ResNet-18 backbone and was trained to detect general dementia, achieving an accuracy of 68.75%.
In this project, we fine-tuned the model specifically for Alzheimer's Disease classification, improving the model's performance to 77% accuracy.

How to Use
Clone the original CEEDNet repository:
git clone https://github.com/ipis-mjkim/caueeg-ceednet
cd caueeg-ceednet

Run the Training Notebook:
Open train.ipynb and run all cells to train the fine-tuned model. This will save a model checkpoint after training.

Run Inference:
After training, use the provided inference script or notebook to evaluate the fine-tuned model on test data.
