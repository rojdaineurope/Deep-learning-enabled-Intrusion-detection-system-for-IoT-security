# Deep-learning-enabled-Intrusion-detection-system-for-IoT-security
IoT traffic requires low latency and real-time analysis ,this Deep learning-based IDS model are detect modern threats accurately in IoT environments.
Deep Learning-Based IoT Intrusion Detection System

This project implements a hybrid CNN–GRU based Intrusion Detection System (IDS) to detect cyber attacks in IoT network traffic.

Traditional IDS solutions struggle with modern attacks and real-time IoT environments.
This project leverages deep learning to classify benign vs attack traffic more effectively.

# Objective

Build an IDS using a hybrid CNN + GRU architecture
Detect malicious IoT network traffic
Reproduce and test the model using real-world datasets

# Model Architecture

The system combines:

CNN → learns spatial patterns in network flow features
GRU → learns temporal dependencies in traffic behavior
Together, they detect complex attack patterns more effectively than standalone models.

# Datasets

NF-UNSW-NB15
NF-CSE-CIC-IDS2018

Both are modern large-scale intrusion detection datasets.



# Training

Epochs: 75
Batch Size: 64
Optimizer: Adam
Loss: Cross Entropy
To handle class imbalance:
SMOTE
Focal Loss
Threshold tuning

## Results


<p align="center">
  <img src="NF_UNSW.png" width="600"/>
</p>


🛠 Tech Stack

Python • PyTorch • FastAPI • aiokafka
