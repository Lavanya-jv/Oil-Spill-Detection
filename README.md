# Oil-Spill-Detection
A deep learning-based project that uses Convolutional Neural Networks (CNN) to classify aerial and satellite images as either Oil Spill or Non-Oil Spill.

# 🚀 Project Overview

Oil spills cause severe environmental and economic consequences. Manual detection is time-consuming and error-prone, hence the need for an automated solution. This project applies CNNs to solve the problem and includes a Python-based Graphical User Interface (GUI) for easy interaction and real-time predictions.

# 💡 Features
-CNN model trained for binary classification (Oil Spill / Non-Oil Spill)
-High accuracy performance (95% on test data)
-GUI for easy image upload and prediction
-Confidence percentage and prediction graph visualization
-Automatic logging of predictions to a CSV file

# 🧠 Technologies Used
-Python
-TensorFlow / Keras
-OpenCV
-Tkinter (for GUI)
-Matplotlib (for confidence graph)
-Pandas (for CSV logging)

# 🗂️ Dataset

Source: Kaggle Oil Spill Dataset

Structure:
train/
validation/
test/

Each folder contains two subfolders:
oil spill/ (Images with oil spills)
non-oil spill/ (Images without oil spills)

# 🏗️ Project Structure

Oil-Spill-Classification/
├── dataset/
│   ├── train/
│   ├── validation/
│   └── test/
├── model/
│   └── oil_spill_cnn.h5
├── gui/
│   └── app.py
├── utils/
│   └── preprocess.py
├── predictions.csv
└── README.md

# ⚙️ How to Run

Clone this repository:

git clone <repository-url>
cd Oil-Spill-Classification

Install dependencies:

pip install -r requirements.txt

Train the model (if not using the pre-trained model):

python train_model.py

Run the GUI:

python gui/app.py

# 💡 Usage
Upload any aerial or satellite image via the GUI.
The application will display:
Prediction (Oil Spill / Non-Oil Spill)
Confidence Percentage
Prediction Confidence Graph
Prediction results will automatically be logged to predictions.csv.

# 📈 Model Performance
Accuracy- 95%
Precision- 94%
Recall- 96%
F1-Score- 95%

# 🔮 Future Work

Integrate video stream support for real-time spill monitoring
Experiment with architectures like ResNet and EfficientNet
Deploy on edge devices for field-ready solutions
