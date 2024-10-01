
# 🏥 **Fine-Tuning Techniques for Medical Image Classification**

📅 **Duration**: September 2024 – October 2024  
**Technologies**: Python, TensorFlow, Keras, MedMNIST, Neural Networks  

---

## 📝 **Project Overview**
This project focuses on medical image classification using the **PathMNIST** dataset, which consists of colorectal cancer histology images. The goal is to explore fine-tuning techniques for neural networks to improve the classification performance on medical images. We experiment with different architectures, hyperparameters, and optimization techniques.

---

## 🎯 **Objectives**
- 🔍 Understand the processing of medical image data for neural network training.
- 🧠 Build a baseline fully connected neural network for image classification.
- 🛠️ Fine-tune and experiment with various model architectures and hyperparameters.
- 📊 Compare the performance of different models and understand how various changes impact results.

---

## 📂 **Dataset**
The **PathMNIST** dataset contains:
- **Training set**: 89,996 images
- **Test set**: 7,180 images
- **Image dimensions**: 28x28 pixels
- **Number of classes**: 9 (each class representing different tissue types)

---

## 🚀 **Tasks**
1. **Data Preparation**:
   - Normalize image pixel values.
   - Flatten images for input into the neural network.
   - Convert labels into one-hot encoded vectors for classification.
   
2. **Baseline Model**:
   - Construct a fully connected neural network with three hidden layers.
   - Compile the model using the Adam optimizer.
   - Train the model for 20 epochs and evaluate its performance.

3. **Fine-Tuning & Comparisons**:
   - Experiment with different activation functions, learning rates, optimizers, and number of trainable parameters.
   - Compare each model’s performance against the baseline.

---

## ⚙️ **Features**
- 🌐 **Baseline Model**: A fully connected neural network with three hidden layers, trained with Adam optimizer and ReLU activations.
- 🛠️ **Model Comparisons**:
   - Changing activation functions in the output layer.
   - Modifying the learning rate.
   - Testing different optimizers.
   - Increasing the number of trainable parameters.
   
---

## 🔧 **Technologies Used**
- **Python**: Programming language.
- **TensorFlow**: Deep learning framework for building and training models.
- **Keras**: High-level API for building neural networks within TensorFlow.
- **MedMNIST**: A lightweight, standardized biomedical image dataset collection.

---

## 📊 **Results**
A detailed table comparing the performance of all models, including metrics like accuracy, loss, and training time, is included in the Jupyter notebook.

---

## 📂 **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/MelikBLK/Fine_Tuning_Techniques_for_Medical_Image_Classification.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install tensorflow medmnist matplotlib
   ```

---

## 📫 **Contact**
Feel free to reach out for any questions or suggestions:
- [LinkedIn](https://www.linkedin.com/in/melik-belkhiria)
- [Email](mailto:belkhiria.melik02@gmail.com)

