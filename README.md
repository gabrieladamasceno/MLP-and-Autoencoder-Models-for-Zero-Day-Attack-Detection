# Evaluating-MLP-and-Autoencoder-Models-for-Zero-Day-Attack-Detection-in-6G-Networks

Sixth Generation (6G) networks promise a deep integration with Artificial Intelligence (AI), enabling intelligent and efficient communication systems. However, this evolution also introduces new cybersecurity threats, including Zero-Day attacks that exploit previously unknown system vulnerabilities. This paper evaluates two widely adopted models, the Multilayer Perceptron (MLP) and the Autoencoder, for attack detection, with a particular focus on Zero-Day attacks. Using a dataset collected from a real 5G network, the study evaluates each model not only in terms of detection performance but also with respect to computational resource consumption. The results indicate that the MLP model outperforms the Autoencoder in both overall classification accuracy and zero-day attack detection, albeit at the cost of higher computational resource usage. 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Stars](https://img.shields.io/github/stars/gabrieladamasceno/MLP-and-Autoencoder-Models-for-Zero-Day-Attack-Detection?style=social)


## About the Project

This repository contains the experiments and models developed for detecting zero-day attacks in 6G networks, using MLP (Multi-Layer Perceptron) and Autoencoder. The goal is to compare performance in terms of detection, generalization, and resource consumption (CPU, memory, time, and energy).

## Structure

├── MLP Model

├── Autoencoder Model

## Results

MLP showed the best overall performance in detecting zero-day attacks.

Autoencoder achieved satisfactory results in unknown anomaly scenarios, with lower computational costs.

## Dataset

The dataset used in this project is **not included** in the repository due to size and licensing restrictions.  

To run the experiments, you need to:  

1. Download the dataset from the original source https://ieee-dataport.org/documents/5g-nidd-comprehensive-network-intrusion-detection-dataset-generated-over-5g-wireless (or use your own dataset).  
2. Place it in your Google Drive (if running on Google Colab) or in the local `data/` folder.  

## Contact

GitHub: https://github.com/gabrieladamasceno 

Email: mgabrieladamasceno@gmail.com

