# Deep-Learning


# Simple MLP for Cat & Dog Classification  

## Overview  
This project explores training **Multi-Layer Perceptrons (MLPs)** with one and two layers on a **small dataset** of cat and dog images. The goal is to understand the impact of **data size limitations** on model performance.  

## Key Challenges  
- **Overfitting:** Due to the small dataset, the model struggles to generalize.  
- **Numerical Instability:** Overflow issues occurred, highlighting the need for proper normalization and larger datasets.  

## Lessons Learned  
- Deep learning models require **large datasets** for effective training.  
- **Normalization and data augmentation** can help improve model stability.  

## Requirements  
- Python (>=3.7)  
- TensorFlow / PyTorch  
- NumPy  
- Matplotlib  

## Running the Project  
```bash
python train.py
