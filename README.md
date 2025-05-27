
# 🌞 SolarGuard: Solar Panel Defect Detection with VGG16

This project applies deep learning to automatically detect and classify defects on solar panels. It helps reduce manual inspections and enhances efficiency by detecting issues like dust, snow, bird droppings, physical damage, and electrical faults.

The model is based on **VGG16 CNN architecture**, fine-tuned for multi-class classification (6 classes) and integrated with **Streamlit** for interactive image upload and predictions.

## 🚀 Key Features
- Classify solar panel images into six categories:
  - Clean
  - Dusty
  - Bird-Drop
  - Electrical-Damage
  - Physical-Damage
  - Snow-Covered
- Data preprocessing, augmentation, and normalization
- Model built on VGG16 with transfer learning
- Visualization of training progress, confusion matrix, and classification report
- Interactive Streamlit app for uploading images and receiving predictions

## 📂 Dataset Structure
```
/Project_Solar_Panel/
    /Clean/
    /Dusty/
    /Bird-Drop/
    /Electrical-Damage/
    /Physical-Damage/
    /Snow-Covered/
```

## 🛠️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/SolarPanel_Defect_Detection.git
cd SolarPanel_Defect_Detection
```

### 2️⃣ Install Dependencies
Create a `requirements.txt` file with:
```
tensorflow
numpy
matplotlib
seaborn
scikit-learn
streamlit
```
Then install them:
```bash
pip install -r requirements.txt
```

## 💻 Run the Streamlit App
```bash
streamlit run app.py
```
Upload solar panel images for real-time condition prediction.

## 📈 Model Overview
- **Base Model**: VGG16 (pre-trained on ImageNet)
- **Input**: 224x224 RGB images
- **Output**: 6 classes
- **Optimizer**: Adam
- **Loss**: Categorical Crossentropy
- **Evaluation**: Accuracy, Precision, Recall, F1-score, Confusion Matrix

## 📊 Visual Outputs
- Training accuracy and loss plots
- Confusion matrix for validation set
- Classification report showing precision, recall, and F1-scores for each class

## 📄 License
This project is licensed under the MIT License.

## 👩‍💻 Author
- **Aishwarya S** ([GitHub Profile](https://github.com/yourusername))
