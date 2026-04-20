# Alzheimer-s-Disease-Classification-using-MRI
Deep learning based approach for classifying Alzheimer’s Disease stages using MRI brain images. A custom CNN is designed and trained to distinguish between four categories: Mild Demented Moderate Demented Non Demented Very Mild Demented 

Highlights
Custom-built CNN architecture (not just transfer learning)
Multi-class classification (4 classes)
End-to-end pipeline: preprocessing → training → evaluation → prediction
Visualization of results (accuracy/loss curves + confusion matrix)
Handles real MRI dataset structure (jpg )

Model Architecture
A deep CNN model was built with:
Multiple Conv2D layers (128 → 512 filters)
Batch Normalization (for stable training)
MaxPooling layers
Fully connected layers (Dense 1024)
Dropout (0.5) to reduce overfitting
Final Softmax layer (4 classes)

Results
Training Accuracy: 99.6 %
Test Accuracy: 95.1%

Dataset : https://www.kaggle.com/datasets/azminur2856/alzheimer-mri-dataset
