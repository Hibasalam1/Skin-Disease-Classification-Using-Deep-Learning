# Skin Disease Classification Using Deep Learning

## Project Overview

This project is a deep learning application that classifies skin lesion images into different skin disease categories. The model is trained using the **HAM10000** dataset and predicts the disease from an uploaded skin image.

---

## Features

* Classifies skin lesion images into **7 disease categories**
* Displays the predicted disease name
* Shows the prediction confidence score
* Provides a simple description of the predicted disease
* Easy to use and understand

---

## Dataset

This project uses the **HAM10000 (Human Against Machine with 10000 Training Images)** dataset.

The dataset contains over **10,000 dermatoscopic skin lesion images** belonging to seven different skin diseases.

Disease Classes:

* Actinic Keratosis (akiec)
* Basal Cell Carcinoma (bcc)
* Benign Keratosis (bkl)
* Dermatofibroma (df)
* Melanoma (mel)
* Melanocytic Nevus (nv)
* Vascular Lesion (vasc)

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* OpenCV

---

## Project Workflow

1. Load the HAM10000 dataset.
2. Organize images into disease folders.
3. Preprocess and normalize the images.
4. Train the deep learning model.
5. Test the model using new skin images.
6. Display the predicted disease, confidence score, and disease description.

---

## Project Structure

```text
Skin-Disease-Classification-Using-Deep-Learning/
│
├── dataset/
├── model/
├── notebook.ipynb
├── README.md
└── requirements.txt
```

---

## How to Run

1. Clone the repository.
2. Install the required libraries.
3. Open the Jupyter Notebook or Python file.
4. Train the model or load the saved model.
5. Predict a skin disease using a new image.

---

## Sample Output

Prediction:

* Disease: Melanoma
* Confidence: 97.85%

Description:
Melanoma is a serious type of skin cancer. Early diagnosis and treatment are important.

---

## Future Improvements

* Build a Streamlit web application.
* Improve model accuracy using transfer learning.
* Add Grad-CAM visualization to explain predictions.
* Generate downloadable prediction reports.

---

## Disclaimer

This project is for educational and research purposes only. It is not intended to replace professional medical advice or diagnosis.
