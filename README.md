
````markdown
# 📸 Source Camera Identification using CNNs

## 📝 Overview
This project implements a Convolutional Neural Network (CNN) to perform **Source Camera Identification (SCI)**.  
The goal is to determine the specific camera model that captured a given image.  
The model is trained on a dataset of images from multiple camera devices and evaluated for its accuracy in identifying the source camera.

## 🧪 Requirements
To run this project, you need the following Python libraries:

```bash
pip install tensorflow numpy matplotlib scikit-learn
````

## 📁 Dataset

The model is trained on the **Forchheim Image Dataset**, which contains 3,851 high-resolution images from 27 different devices.

* **Dataset Access**: [Forchheim Image Dataset](https://gts.ai/dataset-download/forchheim-image-dataset/)

> Tip: Ensure images are preprocessed (resized/cropped) to fit the input shape of the CNN (128x128 pixels recommended).

## 🔧 Model Architecture

* **Input Layer**: Accepts images resized to 128x128 pixels.
* **Convolutional Layers**: Multiple convolution + ReLU layers followed by MaxPooling.
* **Fully Connected Layers**: Dense layers leading to the output layer.
* **Output Layer**: Softmax activation for multi-class classification (one class per camera).

## 📊 Training & Evaluation

* **Optimizer**: Adam
* **Loss Function**: Categorical Cross-Entropy
* **Metrics**: Accuracy
* **Validation**: Uses a separate validation set to monitor performance.

> The notebook visualizes training progress, including accuracy and loss plots, and evaluates the model on the test set with a confusion matrix.

## 🚀 Usage

1. **Open the Colab Notebook**:
   [Google Colab Link](https://colab.research.google.com/drive/1SMIbqP3J6WOPluJ5vS80pawY7VVFUn_1?usp=sharing)

2. **Run All Cells**: Follow instructions to train and evaluate the model.

3. **Modify Dataset or Hyperparameters**:
   You can change the dataset path, batch size, or number of epochs as needed.

## 📈 Results

* Achieves high accuracy in identifying the source camera.
* Confusion matrix and accuracy plots help visualize model performance.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

```

---

If you want, I can also **enhance it with badges, GIFs of model training, and a project flow diagram** to make it look really professional for GitHub.  

Do you want me to do that?
```
