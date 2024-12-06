# Combining Features for Music Genre Classification Using the FMA Dataset  

## Authors  
- Anderson H. Giacomini  
- André R. S. Minari  
- Enrique G. S. Teles  

## Institution  
Instituto de Ciências Matemáticas e de Computação (ICMC), Universidade de São Paulo (USP), Brazil  
Contact: [giacomini@usp.br](mailto:giacomini@usp.br), [andrereliquias@usp.br](mailto:andrereliquias@usp.br), [enriqueteles@usp.br](mailto:enriqueteles@usp.br)  

---

## Overview  

This repository contains the implementation and results of the continuation (part2) of our research on **automatic music genre classification** using the Free Music Archive (FMA) dataset. This work evaluates multiple machine learning and deep learning models to identify music genres based on audio features and a combination of them.  

---

## Abstract  

Automatic music genre classification is a significant challenge in audio processing and machine learning, with practical applications in recommendation systems and the organization of large music collections. This project focuses on the reduced version of the FMA dataset and evaluates the following approaches:  

- **Detach-ROCKET**  
- **InceptionTime**  
- **Convolutional Neural Networks (CNNs)**  
- **Convolutional Recurrent Neural Networks (CRNNs)**  

We use various audio features, including:  
- **Mel-Frequency Cepstral Coefficients (MFCC)**  
- **Chroma**  
- **Spectral Centroid**  
- **Tempo**  
- **Short-Time Fourier Transform (STFT)** 
- **Mel-Spectograms** 

Our findings indicate that the **Detach-ROCKET Ensemble algorithm** with **the combination of all selected features** achieved the highest accuracy for music genre classification.  

---

## Dataset  

This project uses the **Free Music Archive (FMA)** dataset, specifically the **reduced version**, which contains curated and labeled audio tracks suitable for genre classification tasks.  

### Dataset Details  
- **Source:** [Free Music Archive (FMA)](https://github.com/mdeff/fma)  
- **Size:** 8,000 tracks (30 seconds each) across 8 balanced genres  
- **License:** Creative Commons  
- **Features:** Audio tracks are accompanied by metadata, including genre labels and additional details like artist and album information.  

For more information about the dataset, visit the [official FMA dataset documentation](https://github.com/mdeff/fma).  
