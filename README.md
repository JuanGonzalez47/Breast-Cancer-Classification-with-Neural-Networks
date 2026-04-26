# Breast Cancer Classification with Neural Networks

This project focuses on breast cancer classification using the Al-Dhabyani et al. dataset. It explores a variety of machine learning and deep learning models, starting from classic algorithms (LMS, MLP, Perceptron) to advanced PyTorch-based Convolutional Neural Networks (CNNs) and Transfer Learning with ResNet.

<img width="1024" height="469" alt="image" src="https://github.com/user-attachments/assets/ed10d6eb-a8d2-47ed-bb6d-208d8ec540dd" />

## Project Structure

- **dataset/**: Contains the image data (benign/malignant images and masks).
- **notebooks/**: Jupyter Notebooks for each model and experiment:
	- `Perceptron.ipynb`: Perceptron and Pocket algorithm for classification.
	- `LMS.ipynb`: Least Mean Squares (LMS) model.
	- `MLP.ipynb`: Multi-Layer Perceptron.
	- `ImageCNN.ipynb`: CNNs with transfer learning, Grad-CAM visualization, and data augmentation.
	- `MaskCNN.ipynb`: CNNs using mask-based features.
- **results/**: Output results, figures, and evaluation metrics.
- **docs/**: Project documentation and related papers.

## Main Features

- **Data Preprocessing**: Includes normalization, augmentation, and ROI cropping.
- **Modeling**:
	- Classic ML: Perceptron, Pocket, LMS, MLP
	- Deep Learning: Custom CNNs, Transfer Learning with ResNet
- **Training Strategies**: Implements Bold Driver, Weighted Loss, Early Stopping, and Stratified Splits.
- **Interpretability**: Grad-CAM visualizations to interpret CNN decisions.
- **Evaluation**: F1-score, accuracy, confusion matrix, and robust validation/test splits.

## How to Run

1. Install dependencies:
	 ```bash
	 pip install -r requirements.txt
	 ```
2. Open the desired notebook in Jupyter or VS Code and run the cells step by step.

## Dataset

The dataset is from Al-Dhabyani et al. and contains benign and malignant breast tissue images with corresponding masks. **Note:** Large files like `dataset.zip` are not tracked by Git.

## Results

- Demonstrates the impact of tumor morphology and region-of-interest (ROI) selection on classification performance.
- Shows the benefits of transfer learning and interpretability with Grad-CAM.

## References

- Al-Dhabyani, W., Gomaa, M., Khaled, H., & Fahmy, A. (2020). Dataset of breast ultrasound images. Data in Brief, 28, 104863.

---
**Author:** JuanGonzalez47 - Juan Pablo González Blandón
