# 🐾 Pet Classification Using Deep Learning

A Deep Learning project that classifies pet images using Convolutional Neural Networks (CNNs). This project was developed using Python, TensorFlow/Keras, and Jupyter Notebook to demonstrate image classification techniques in computer vision.

---

## 📖 Project Description

Pet classification is an image recognition task where a machine learning model learns visual patterns from pet images and predicts the correct category for unseen images.

This project covers the complete workflow of a Deep Learning image classification system, including:

* Image preprocessing
* Data augmentation
* CNN model development
* Model training and validation
* Performance evaluation
* Image prediction

---

## 🎯 Objectives

* Understand the fundamentals of image classification.
* Learn how Convolutional Neural Networks (CNNs) work.
* Build and train a Deep Learning model using TensorFlow/Keras.
* Evaluate model performance on unseen images.
* Apply computer vision concepts to a real-world problem.

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

---

## 📂 Project Structure

```text
Pet_class/

├── images/
│   ├── train/
│   ├── validation/
│   └── test/
│
├── pet_classifier.ipynb
├── ClassificationOfPets_SS.pdf
└── README.md
```

---

## ⚙️ Methodology

### 1. Data Collection

A dataset containing labeled pet images is used for training and testing the model.

### 2. Data Preprocessing

The images are:

* Resized to a fixed dimension
* Normalized for better learning
* Organized into training and validation sets

### 3. Data Augmentation

To improve model generalization and reduce overfitting:

* Rotation
* Zooming
* Flipping
* Shifting

are applied during training.

### 4. Model Development

A Convolutional Neural Network (CNN) architecture is used consisting of:

* Convolution Layers
* Max Pooling Layers
* Flatten Layer
* Dense Layers
* Output Layer

### 5. Model Training

The model is trained on the prepared dataset using:

* Adam Optimizer
* Binary/Categorical Cross-Entropy Loss
* Accuracy Metric

### 6. Evaluation

Model performance is evaluated using:

* Training Accuracy
* Validation Accuracy
* Loss Curves

### 7. Prediction

The trained model predicts the category of new pet images based on learned visual features.

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/Pet_class.git
```

### Navigate to the Project Directory

```bash
cd Pet_class
```

### Install Dependencies

```bash
pip install tensorflow numpy pandas matplotlib jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Open

```text
pet_classifier.ipynb
```

Run all cells to train and test the model.

---

## 📊 Results

The CNN model successfully learns image features from pet images and performs classification on unseen data.

Example Output:

```text
Input Image: Pet Image

Predicted Class: Dog

Confidence Score: 98.4%
```

---

## 📚 Concepts Learned

* Deep Learning
* Computer Vision
* Image Classification
* Convolutional Neural Networks (CNNs)
* Data Augmentation
* TensorFlow & Keras
* Model Evaluation

---

## 🔮 Future Enhancements

* Add more pet categories
* Improve model accuracy with larger datasets
* Use Transfer Learning (ResNet, MobileNet, VGG16)
* Deploy as a web application using Flask or Streamlit
* Create a real-time image prediction system

---

## 👩‍💻 Author

**Riya Harugop**

Computer Science (AIML)

PES College

LinkedIn: https://www.linkedin.com/in/riya-harugop-37a67a33a

Email: [riya.harugop@gmail.com](mailto:riya.harugop@gmail.com)

---

## 📄 License

This project is created for educational and learning purposes.
