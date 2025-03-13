# Lung Disease Classification using CNN Models

# 📌 Project Overview

This project classifies lung diseases from chest X-ray images using deep learning models. 
Multiple Convolutional Neural Network (CNN) architectures, including VGG16, ResNet50, DenseNet121, InceptionV3, Xception, and EfficientNetB3, have been used to achieve high classification accuracy.

# 📂 Dataset

The dataset consists of X-ray images categorized into four classes:

COVID-19

Normal

Pneumonia

Tuberculosis

# Dataset Structure:

/data
 
   ├── train/       # Training images (6326 images)
   
   ├── val/         # Validation images (38 images)
   
   ├── test/        # Test images (771 images)

# ⚙️ Implementation Steps

Data Preprocessing: Image augmentation techniques (rotation, zoom, flips) are applied to improve model generalization.

Model Training: Different CNN architectures are trained and optimized using Adam optimizer and early stopping.

Evaluation Metrics: Models are evaluated using accuracy, loss, and confusion matrices.

Comparison of Models: The best-performing model is selected based on performance metrics.

# 📊 Results


![image](https://github.com/user-attachments/assets/b8de4625-5f64-49dc-9232-fb5cea21258e)



The best model achieves 63% validation accuracy, making it a reliable classifier for lung diseases.

# Model Comparison Visualization

![model_comparision](https://github.com/user-attachments/assets/c1db0014-1542-4b3c-a936-65581a4ead6a)


# 📌 Future Improvements

Fine-tuning hyperparameters for better accuracy.

Using larger datasets for improved generalization.

Implementing attention mechanisms to enhance model focus on critical areas.




# ⭐ Acknowledgments

Dataset sourced from Kaggle

TensorFlow and Keras for deep learning models

If you find this project useful, consider ⭐ starring the repo!

nehith0315@gmail.com
