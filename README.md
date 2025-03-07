# Interpretable Prototype-Based Autoencoder for Melanoma Diagnosis  

This project presents an **interpretable deep learning model** for melanoma detection, combing **autoencoders** with **prototype-network**. The model realize transparency by visaulizing feature representations and prototype images and explain its decision-making by similarity calculating.

## Features  
- **Prototype-Based Autoencoder**: Combines autoencoder architecture with prototype learning for better interpretability.  
- **Feature Visualization**: Extracts and reconstructs key features, allowing insight into decision-making.  
- **Example-Based Explanations**: Uses prototype images to illustrate classification typical categories.  
- **Optimized Distance Strategies**: Implements multiple distance strategy (Euclidean, Manhattan, etc.) for improved performance and transparency.  
- **Dataset**: Designed for **melanoma detection** using the **ISIC2018 dataset**.  

## Model Architecture  
The model consists of:  
- **An Autoencoder Network**: Performs **feature extraction** and **reconstruction**.  
- **A Prototype Network**: Learns representative prototypes and classifies images based on similarity.  
- **Distance-Based Similarity Measures**: Optimizes classification and presentation using multiple distance strategies.  

## Dataset  
- **ISIC2018 Dataset**: 11,720 dermoscopic images  
- **Classes**: Melanoma (1,305 images) & Non-Melanoma (10,415 images)  
- **Preprocessing**: Image resizing, augmentation, and oversampling for class balance  

<p align="center">
  <img src="assets/model_architecture.png" width="600">
</p>

