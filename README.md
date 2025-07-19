# Tree_classification

1. Used Transfer Learning (MobileNetV2)
Switched from a custom CNN to MobileNetV2, a powerful pretrained model.

Significantly improved accuracy and generalization on a small dataset.

2. Added Data Augmentation
Applied real-time transformations (flip, zoom, rotation) to reduce overfitting and simulate diverse data.

3. Applied Normalization
Rescaled pixel values to [0, 1] for faster convergence and better performance.

4. Implemented Fine-Tuning
Unfroze part of the pretrained model and trained further with a lower learning rate to boost validation accuracy.

5. Enhanced Performance Monitoring
Plotted training/validation accuracy and loss curves.

6. Custom Image Prediction
Integrated functionality to classify new/unseen leaf images.
