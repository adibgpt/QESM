# Quantum-Enhanced ML Emulation Framework for Earth and Climate Modeling (QESM)

This repository contains the research and implementation details of **QESM** (Quantum-Enhanced Machine Learning Emulation Framework), a novel approach to enhance climate and Earth system modeling through quantum computing techniques. The QESM framework integrates advanced quantum machine learning (QML) architectures to significantly improve prediction accuracy and computational efficiency in climate modeling.

![image](https://github.com/adibgpt/QESM/blob/5732ba0b73aac412beb11cb217bd2a2f78613559/Images/Picture8.png)

## Overview

Current climate models often face limitations in resolution and computational constraints, reducing the precision of weather forecasts and long-term predictions. QESM addresses these issues by replacing conventional ML models with quantum-enhanced counterparts, including:

- **Quantum Convolutional Neural Networks (QCNN)**

![image](https://github.com/adibgpt/QESM/blob/222c24003def74d365bc7897a4e9f69189b5ea31/Images/Picture1%20(1).png)

- **Quantum Multilayer Perceptrons (QMLP)**

![image](https://github.com/adibgpt/QESM/blob/f1354c0903a7594daad1a4187c6416b263a5112a/Images/Picture105.png)

- **Quantum Encoder-Decoder (QED)**
  
![image](https://github.com/adibgpt/QESM/blob/0698b8f3fadcc546f4e2f40833ac2fb10893d65a/Images/Picture111110.png)

These quantum models are further optimized using a **meta-ensemble approach**, combining their strengths to achieve state-of-the-art performance.

## Key Features

1. **Advanced Quantum Architectures**:
   - **QCNN**: Optimized for spatial data processing with quantum convolutional layers and quantum activation functions (Q-ReLU).
   - **QMLP**: Integrates quantum principles for high-dimensional data analysis, leveraging superposition and entanglement.
   - **QED**: Implements a quantum autoencoder for dimensionality reduction and reconstruction.

2. **ClimSim Dataset**:
   - Utilizes the **ClimSim** dataset, a 41.2TB collection of high-resolution climate data for training ML emulators, enabling comprehensive analysis of Earth system variables.

3. **Meta-Ensemble Learning**:
   - Combines predictions from QCNN, QMLP, and QED to maximize prediction accuracy and generalization.

4. **Quantum Dropout and Activation Functions**:
   - Introduces novel quantum dropout strategies and activation functions (e.g., Q-ReLU) to improve training stability and model robustness.

## Key Results

The QESM framework demonstrates substantial improvements in prediction accuracy across various climate variables, including:

| Variable               | Classical MAE | Quantum MAE | Classical R² | Quantum R² |
|------------------------|---------------|-------------|--------------|------------|
| Surface Pressure (Pa)  | 18.85         | 9.46        | 0.944        | 0.995      |
| Latent Heat Flux (W/m²)| 3.36          | 0.36        | -            | -          |
| Surface Temperature (K)| 10.83         | 3.87        | 0.927        | 0.991      |

![image](https://github.com/adibgpt/QESM/blob/4736599aef56ed297717d5ec1234c0769a52b26a/Images/Picture21.png)
![image](https://github.com/adibgpt/QESM/blob/4736599aef56ed297717d5ec1234c0769a52b26a/Images/Picture31.png)

## Contributions

1. **Quantum Integration in Climate Models**:
   - Replacing classical ML models with quantum-enhanced alternatives.

2. **Hybrid Quantum-Classical Framework**:
   - Efficient integration of quantum and classical components for optimal performance.

3. **Comprehensive Analysis**:
   - Detailed evaluation of quantum methods under various scenarios, including noise levels and regularization.

![image](https://github.com/adibgpt/QESM/blob/a928935630bb061761b67885d6f2e978eb0d849c/Images/Picture1006.png)
![image](https://github.com/adibgpt/QESM/blob/a928935630bb061761b67885d6f2e978eb0d849c/Images/Picture1007.png)
![image](https://github.com/adibgpt/QESM/blob/a928935630bb061761b67885d6f2e978eb0d849c/Images/Picture1008.png)

## How to Use

### Prerequisites

- Quantum computing libraries (e.g., Qiskit, Pennylane)
- High-performance computing infrastructure for large datasets (e.g., ClimSim)

### Installation

```bash
git clone https://github.com/example/QESM.git
cd QESM
pip install -r requirements.txt
