Breast Cancer Prediction Using Ultrasound Imaging: 
This project focuses on building a robust deep learning model to classify breast cancer using ultrasound images from the BUSI Dataset. The goal is to distinguish between benign, malignant, and normal tissue using convolutional neural networks (CNNs) and transfer learning strategies.

📌 Objectives
Build and train CNN models using pre-trained architectures like VGG16 and ResNet50.

Apply advanced image preprocessing and data augmentation techniques (using Albumentations).

Optimize model performance with hyperparameter tuning (via Keras Tuner).

Evaluate the model using classification metrics such as confusion matrix and classification report.

🛠️ Technologies & Libraries
Python, TensorFlow, Keras

CNNs (VGG16, ResNet50)

Albumentations for data augmentation

Keras Tuner for hyperparameter optimization

fpdf for report generation

Matplotlib & Seaborn for visualization

📁 Dataset
Dataset used: BUSI Dataset (Dataset_BUSI_with_GT)

Contains ultrasound images categorized into normal, benign, and malignant classes with associated masks.

🚀 Highlights
End-to-end pipeline from data preprocessing to evaluation

Transfer learning improves generalization and reduces training time

Automated PDF report generation of model performance

📊 Results
Performance was assessed using metrics like precision, recall, and F1-score. The models demonstrated promising accuracy in classifying breast tissue images across multiple categories.
