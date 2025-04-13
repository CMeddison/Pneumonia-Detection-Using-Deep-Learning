# Pneumonia-Detection-Using-Deep-Learning
A deep learning project to classify chest X-ray images into **Pneumonia** or **Normal**, using a convolutional neural network (CNN). Built and trained using the Kaggle [Chest X-ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) dataset, this model aims to support early detection of pneumonia via automated diagnosis.

---

## 🗂️ Dataset
- **Source:** [Kaggle Chest X-ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- Includes over **5,000** X-ray images labeled as `PNEUMONIA` or `NORMAL`.

---

## 📌 Project Objectives
- Build a CNN-based image classifier to detect pneumonia.
- Preprocess image data and handle class imbalance.
- Evaluate model performance using accuracy, precision, recall, and confusion matrix.
- Visualize learning using training curves and Grad-CAM (optional).
- Highlight the role of AI in medical diagnostics.

---

## 🧰 Tools & Technologies
- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🚀 How to Run the Project

```bash
# Clone the repo
git clone https://github.com/yourusername/pneumonia-detection-cnn.git
cd pneumonia-detection-cnn

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Pneumonia_Detection.ipynb
