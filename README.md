# **ssl_techniques**

This repository is part of my Master's Thesis: **Exploring Semi-Supervised Methods in Magnetic Resonance Imaging Analysis**. It provides the necessary code to train and evaluate various Semi-Supervised Learning (SSL) techniques for medical image segmentation.

---

## **Datasets**  
This work utilizes the following datasets:  
- **LA**: Left Atrium dataset  
- **BraTS-Africa**: Brain Tumor Segmentation dataset  

---

## **Implemented Techniques**  
The repository includes implementations of the following SSL techniques:  
- **MT**: Mean Teacher  
- **DAN**: Deep Adversarial Network  
- **ADVENT**: Adversarial Entropy Minimization  
- **CPS**: Cross Pseudo Supervision  
- **SCC**: Semi-Supervised Contrastive Consistency  
- **DCT**: Deep Co-Training  

---

## **Main contributions**    
- Tailored Dataloader
- Updated validation functions
- Customized the training code

---

## **Environment**  
The code is optimized for use with **Google Colab** and can be adapted to other environments if needed.  

---

## **Acknowledgments**  
The repository builds upon and adapts existing implementations:  
- **SCC**: [PerceptionComputingLab/SCC](https://github.com/PerceptionComputingLab/SCC)  
- **SSL4MIS**: [HiLab-git/SSL4MIS](https://github.com/HiLab-git/SSL4MIS)  
