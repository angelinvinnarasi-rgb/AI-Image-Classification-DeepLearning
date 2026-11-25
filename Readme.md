# AI-Based Image Classification System Using Deep Learning

## Project Overview

This project focuses on developing an AI-based image classification system using Deep Learning techniques and Computer Vision.

The system uses the CIFAR-10 dataset to classify images into 10 different object categories using a Custom Convolutional Neural Network (CNN) and Transfer Learning with MobileNetV2.

The main objective is to understand CNN architecture, implement Transfer Learning, evaluate model performance, and compare both approaches.

## Objectives

- Load and explore the CIFAR-10 dataset.
- Perform image preprocessing and normalization.
- Build and train a Custom CNN model.
- Implement Transfer Learning using MobileNetV2.
- Evaluate model performance using accuracy, loss, confusion matrix, and classification report.
- Perform image predictions and visualize results.
- Compare Custom CNN and Transfer Learning models.

## Dataset

**Dataset:** CIFAR-10

**Source:** https://www.cs.toronto.edu/~kriz/cifar.html

The CIFAR-10 dataset contains 60,000 color images of size 32 × 32 pixels divided into 10 classes.

- Training images: 50,000
- Testing images: 10,000
- Image dimensions: 32 × 32 × 3
- Number of classes: 10

### CIFAR-10 Classes

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code

## Project Workflow

### Task 1 – Data Preparation

- Dataset loading and exploration
- Image preprocessing
- Image resizing
- Pixel normalization
- Train-test dataset preparation
- Sample image visualization
- Class label handling

### Task 2 – CNN Model Development

- Custom CNN architecture development
- Convolutional layers
- Max Pooling layers
- Dropout
- Flatten and Dense layers
- Softmax classification
- Model training and evaluation

### Task 3 – Transfer Learning

Implemented MobileNetV2 using Keras Applications.

- Loaded pretrained MobileNetV2.
- Froze pretrained base layers.
- Added custom classification layers.
- Trained and evaluated the model.

### Task 4 – Prediction and Visualization

- Test image predictions
- Actual vs predicted labels
- Correctly classified image visualization
- Misclassified image visualization
- Training and validation accuracy plots
- Training and validation loss plots

### Task 5 – Model Analysis and Documentation

- CNN vs Transfer Learning comparison
- Model performance analysis
- Advantages and limitations
- Implementation challenges
- Real-world applications
- Future improvements

## Model Performance Comparison

The following results were obtained on the CIFAR-10 test dataset.

| Evaluation Metric | Custom CNN | MobileNetV2 |
|---|---:|---:|
| Test Accuracy | 70.43% | 86.45% |
| Test Loss | 0.8411 | 0.4349 |

### Performance Analysis

- Custom CNN achieved 70.43% test accuracy.
- MobileNetV2 achieved 86.45% test accuracy.
- MobileNetV2 performed better by 16.02 percentage points.
- MobileNetV2 also achieved lower test loss.

## Project Structure

```text
AI_Image_Classification_DeepLearning/
│
├── dataset/
│
├── models/
│   ├── custom_cnn.keras
│   └── mobilenetv2_model.keras
│
├── notebooks/
│   └── AI_Image_Classification.ipynb
│
├── outputs/
│   ├── model_comparison.png
│   ├── cnn_confusion_matrix.png
│   └── mobilenet_confusion_matrix.png
│
├── test_images/
│
├── README.md
├── requirements.txt
└── .gitignore
```

Note: Dataset files and Python virtual environments are excluded from GitHub. The models and output files should be included if available.

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/AI-Image-Classification-DeepLearning.git
```

### 2. Navigate to the project folder

```bash
cd AI-Image-Classification-DeepLearning
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the environment (Windows)

```bash
.venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook inside the `notebooks` folder and execute the cells.

The CIFAR-10 dataset can be downloaded from the official dataset source.

## Real-World Applications

- Medical image classification
- Industrial quality inspection
- Retail product categorization
- Security and surveillance
- Autonomous vehicle object recognition

## Future Improvements

- Fine-tuning pretrained MobileNetV2 layers.
- Experimenting with EfficientNetB0 and ResNet50.
- Applying data augmentation techniques.
- Hyperparameter optimization.
- Deploying the model using Flask or Streamlit.
- Developing a real-time image classification application.

## Conclusion

This project demonstrates the application of Deep Learning and Computer Vision for image classification using Custom CNN and Transfer Learning.

MobileNetV2 achieved 86.45% test accuracy, outperforming the Custom CNN, which achieved 70.43%.

The project provided practical experience in image preprocessing, CNN development, Transfer Learning, model evaluation, and prediction visualization.

---

**Project Category:** Data Science / Deep Learning / Computer Vision

**Dataset:** CIFAR-10

**Models:** Custom CNN and MobileNetV2