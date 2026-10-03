# Transformer-and-gnn-based-cellular-traffic-prediction-using-Federated-Learning


# 📡 Cellular Traffic Prediction Using Federated Learning and Graph-LSTM

<p align="center">
  <b>Major Project – Artificial Intelligence & Machine Learning</b><br>
  Telecom Traffic Prediction using LSTM, FedNova and Graph-LSTM
</p>

---

## 🚀 Run the Project in Google Colab

Click the button below to open the complete project notebook in Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VSZNCkJWhPxQhuK0slLLu3quHgZh1rgC)

## 📌 Overview

This project focuses on **cellular Internet traffic prediction** using Deep Learning, Federated Learning, and Graph Neural Networks.

The project is inspired by the research paper:

> **Transformer and Graph Neural Network-Based Federated Learning for Cellular Traffic Prediction With Sustainability Analysis**

The methodology is adapted to the **Telecom Italia Milan Telecommunications Dataset**.

The project is developed progressively as:

```text


Centralized LSTM
       ↓
Federated LSTM + FedNova
       ↓
Graph-LSTM
       ↓
Transformer + Sustainability Analysis

SYSTEM ARCHITECTURE: 

                 Milan Telecom Dataset
                         │
                         ▼
                  Data Preprocessing
                         │
                         ▼
                 Feature Engineering
                         │
                         ▼
                 Time-Series Windows
                         │
                         ▼
                  Centralized LSTM
                         │
                         ▼
                  Simulated Clients
                    /           \
                   /             \
                  ▼               ▼
             Client 1          Client 2
             Local LSTM        Local LSTM
                  \               /
                   \             /
                    ▼           ▼
                       FedNova
                    Aggregation
                         │
                         ▼
                    Global LSTM
                         │
                         ▼
                    Spatial Graph
                         │
                         ▼
                 Graph Aggregation
                         │
                         ▼
                     LSTM (128)
                         │
                         ▼
                    Dense Layer
                         │
                         ▼
                Traffic Prediction
                         │
                         ▼
                    Evaluation
