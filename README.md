# AI-Generated Image Detection Using Transfer Learning with Explainable AI

## Project Overview

This project detects whether a facial image is **real** or **AI-generated** using **Transfer Learning** with **MobileNetV2**. To improve model interpretability, **Grad-CAM (Gradient-weighted Class Activation Mapping)** is used to visualize the regions of an image that influence the model's predictions.

The project was developed as part of my **M.Sc. Data Analytics** final-year project.

---

## Features

* Binary classification of **Real** vs **AI-Generated** face images.
* Transfer Learning using **MobileNetV2**.
* Explainable AI using **Grad-CAM**.
* Image preprocessing and model evaluation.
* Streamlit-based web application for image prediction.

---

## Technologies Used

* Python
* TensorFlow / Keras
* MobileNetV2
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Streamlit

---

## Dataset

This project uses the **140K Real and Fake Faces** dataset from Kaggle.

**Dataset:** https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces

> The dataset is not included in this repository because of its large size. Please download it separately from Kaggle before running the notebook.

---

## Model

* **Base Model:** MobileNetV2 (ImageNet pretrained)
* **Input Size:** 224 × 224
* **Classification:** Binary (Real / AI-Generated)
* **Framework:** TensorFlow / Keras

---

## Results

The trained model achieved approximately **88% test accuracy** on the evaluation dataset.

Model evaluation includes:

* Accuracy
* Confusion Matrix
* Classification Report
* Grad-CAM Visualizations

---

## Repository Contents

* `AI_Generated_Image_Detection.ipynb` – Model development and training notebook
* `final_model.keras` – Trained model
* `streamlit_app.py` – Streamlit application (if included)
* `requirements.txt` – Required Python packages

---

## Installation

Clone the repository:

```bash
git clone https://github.com/anetphilomina-code/AI-Generated-Image-Detection.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Download the dataset from Kaggle and place it in the appropriate directory before running the notebook.

---

## Future Improvements

* Improve classification accuracy with additional fine-tuning.
* Evaluate the model on more diverse AI-generated image datasets.
* Deploy the application on a cloud platform.
* Explore newer vision models for improved performance.

---

## Author

**Anet Philomina**

GitHub: https://github.com/anetphilomina-code
