# Federated Learning Experiments

This repository contains research-oriented experiments in Federated Learning (FL), using MovieLens 100k and MNIST datasets.  
The goal is to analyze the impact of:

- number of clients  
- number of local epochs  
- non-IID data distribution  
- model architecture  
- FedAvg aggregation behavior  

This project follows a **research + engineering** structure (NVIDIA-ready).

---

## 📂 Repository Structure


---

## 🧪 Experiments

### 1️⃣ FL: Local Epochs
- Epochs: 1–15  
- Metric: RMSE  
- Dataset: MovieLens 100k  

Notebook: `notebooks/FL_epochs_experiment.ipynb`

---

### 2️⃣ FL: Clients Count
- Clients: 2, 5, 10, 20, 30, 40, 50, 75, 100  
- Metric: RMSE  

Notebook: `notebooks/FL_clients_experiment.ipynb`

---

### 3️⃣ FL: Non-IID Distribution
- Test IID vs non-IID  
- Compare convergence and RMSE  

Notebook: `notebooks/FL_nonIID_experiment.ipynb`

---

### 4️⃣ FL: MNIST Demo
Simple 2-client federated learning for image classification.

Notebook: `notebooks/FL_MNIST_demo.ipynb`

---

## 🚀 Future Work

- FedProx  
- Personalized FL  
- Secure aggregation  
- Differential privacy  
- Edge-device simulation (NVIDIA Jetson)

---
