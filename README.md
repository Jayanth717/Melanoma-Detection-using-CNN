# Melanoma Detection using Convolutional Neural Networks (CNN)

## About the Project
This project focuses on detecting **melanoma (a type of skin cancer)** from dermoscopic images using **deep learning techniques**. Multiple CNN architectures were explored, including transfer learning models, and a **custom CNN** was designed that achieved better performance compared to standard architectures.

The final trained model is deployed using a **Gradio-based web interface**, allowing users to upload skin lesion images and receive real-time predictions.

---

## Key Features
- Image classification for melanoma vs benign lesions
- Custom CNN architecture with improved performance
- Comparison with pre-trained models (ResNet, VGG, EfficientNet)
- Class imbalance handling using imbalanced-learn techniques
- Interactive Gradio web application for predictions
- Model saved and reused for inference

---

## Technologies Used
- **Python**
- **TensorFlow / Keras**
- **Scikit-learn**
- **OpenCV & Pillow**
- **Matplotlib & Seaborn**
- **Imbalanced-learn**
- **Gradio**

---

## How to Run the Project

### Step 1: Clone the repository
git clone https://github.com/Jayanth717/Melanoma-Detection-using-CNN.git

### Step 2: Navigate to the project directory
cd Melanoma-Detection-using-CNN

### Step 3: Install dependencies
pip install -r requirements.txt

### Step 4: Run the Gradio application
python SkinLesionDetector_Gradio.py

### Model Details

Best Model: Custom CNN
Saved Model File: skin_cancer_prediction.h5
Reason for Selection: Achieved better accuracy and generalization compared to transfer learning models on the given dataset.

### Dataset

The project uses dermoscopic skin lesion images sourced from publicly available datasets (e.g., HAM10000).
Due to size constraints, the full dataset is not included in this repository.

### Results

Improved performance using a custom CNN architecture
Effective handling of class imbalance
Real-time predictions through a user-friendly web interface
Screenshots of predictions and UI are available in the Screenshots/ folder.

### Author

Jayanth Kumar

Machine Learning | Deep Learning | Data Analytics
