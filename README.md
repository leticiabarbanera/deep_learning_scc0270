# Neural Networks

## INTRODUCTION

This repository refers to the final submission for the course **SCC0270 - Neural Networks**. The objective of the project was to develop and train a neural network capable of classifying chest X-ray images into two categories: healthy individuals and patients diagnosed with COVID-19. The dataset used is publicly available at: https://github.com/ieee8023/covid-chestxray-dataset.

This is a **binary classification problem**:
- With COVID-19 (label 0): 342 images  
- Healthy (label 1): 193 images  

The dataset is slightly imbalanced between classes (approximately 65% - 35%), which is important to consider for the following steps.

This repository is organized as follows: each file name indicates which neural networks were trained within it, in the same order they appear in the code. Each network is organized within a specific section or index in the notebook, making it easier to locate.  
The preambles of the files are the same across notebooks (data import + general functions, such as training and validation).  
The notebooks can be viewed in any order, but we recommend following the **chronological sequence** we worked in, as described below. For clarity, we list at the end of this README.md the order in which the files should be consulted and which networks are contained in each. We’ve organized this structure to make understanding easier.

---

## CHRONOLOGICAL ORDER OF FILES

### FIRST SUBMISSION – IMAGE FOCUS

1. Check `cnnsimples_resnet18_resnet34_shufflenet_efficientnet.ipynb` for simple CNNs  
2. Check the entire `familiadensenet_familiaresnet.ipynb` notebook  
3. Check the entire `transferlearning_chexnet_torchxrayvision.ipynb` notebook  
4. For ResNet-18 and ResNet-34, check:
   - `cnnsimples_resnet18_resnet34_shufflenet_efficientnet.ipynb`  
   - `customcnn_resnet_squeezenet_mobilenet.ipynb`  
5. For ShuffleNet and EfficientNet, check:
   - `cnnsimples_resnet18_resnet34_shufflenet_efficientnet.ipynb`  
6. Check the entire `shufflenet_googlenet.ipynb` notebook  
7. For SqueezeNet and MobileNet, check:
   - `customcnn_resnet_squeezenet_mobilenet.ipynb`  
8. Check the entire `mobilenet.ipynb` notebook  

---

### SECOND SUBMISSION – TEXT FOCUS

1. Check the `processing_texts.ipynb` notebook  

---

### FINAL SUBMISSION – MULTIMODAL NETWORK

1. `errors_analysis.ipynb`  
2. `multimodal.ipynb`  
3. `modelo_multimodal_final.ipynb`  

---

**Note**: The main research papers referenced during development are cited within the notebooks, along with direct links for access.
