# Tuberculosis Detection from Chest X-rays — CNN vs ResNet-50

This repository contains the notebook **Final_Dl_lab.ipynb**, which applies deep learning techniques for the detection of **Tuberculosis (TB)** from chest X-ray images.

---

##  Work Done in the Notebook

1. **Dataset**  
   - Used the [Tuberculosis (TB) Chest X-ray Database](https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset)  
   - Dataset contains:
     - 700 TB-positive chest X-rays  
     - 3,500 Normal chest X-rays  
   - Data organized into folders for training and evaluation  

2. **Data Preparation**  
   - Preprocessing and augmentation applied using `torchvision.transforms`  
   - Training, validation, and test splits created  

3. **Custom CNN Model**  
   - Implemented a convolutional neural network from scratch  
   - Layers: convolution, pooling, fully connected, dropout, batch normalization  
   - Trained and validated on the chest X-ray dataset  

4. **Pretrained Model — ResNet-50**  
   - Loaded pretrained ResNet-50 from `torchvision.models`  
   - Fine-tuned the model for TB detection  
   - Evaluated using the same dataset and metrics  

5. **Evaluation and Comparison**  
   - Accuracy and loss curves plotted for both CNN and ResNet-50  
   - Confusion matrix used to analyze classification quality  
   - Comparison of CNN vs ResNet-50 performances  

---

##  File

- **Final_Dl_lab.ipynb** → includes dataset preparation, CNN implementation, ResNet-50 fine-tuning, evaluation, and model comparison.
