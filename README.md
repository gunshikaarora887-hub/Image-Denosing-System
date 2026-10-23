# 🧠 AI Image Denoising System

A Deep Learning based Image Denoising application built using TensorFlow, OpenCV and Streamlit.

---

## Features

- Upload any image
- Add Gaussian Noise
- Remove noise using DnCNN
- Download denoised image
- Interactive Streamlit interface
- Adjustable noise level
- PSNR and SSIM metrics

---

## Technologies

- Python
- TensorFlow
- OpenCV
- NumPy
- Streamlit
- Deep Learning

---

## Project Structure

```
Image Denoising System
│
├── app.py
├── train.py
├── predict.py
├── models/
├── utils/
├── dataset/
└── dncnn_model.keras
```

---

## Installation

```bash
git clone <repository-link>
cd Image-Denoising-System

pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## Model

Model Used:

**DnCNN (Deep Convolutional Neural Network)**

Training:

- Gaussian Noise
- TensorFlow/Keras
- MSE Loss
- Adam Optimizer

---

## Author

**Shambhav Kumar**
