# 🧠 Brain Tumor Detection using Deep Learning

![Brain Tumor Detection Banner](https://img.freepik.com/free-vector/brain-tumor-abstract-concept-illustration_335657-3681.jpg?w=1380&t=st=1712387356~exp=1712387956~hmac=5596c6c8791b53cc2a19bb232108a18d88df16f8b9b0f22fd00b94fbd7b3f5c1)

## 📌 Project Overview

This project focuses on detecting **brain tumors** from MRI images using a Convolutional Neural Network (CNN). It uses image classification techniques in deep learning to accurately distinguish between tumor and non-tumor brain scans.

The model can be trained on a labeled dataset and tested for real-time applications, potentially aiding radiologists in medical diagnostics.

---

## 🧪 Technologies Used

- 🐍 Python 3.x
- 📊 NumPy, Matplotlib
- 🧠 TensorFlow / Keras
- 🖼 OpenCV / PIL
- 📝 Jupyter Notebook

---

## 🧬 Dataset

The dataset used contains **MRI images** of human brains categorized into:
- `yes` — Brain Tumor Present
- `no` — No Brain Tumor

Each image is preprocessed and resized for consistent input to the CNN.

---

## 🚀 Features

- ✅ Image preprocessing (resizing, normalization)
- ✅ Binary classification using CNN
- ✅ Accuracy and loss visualization
- ✅ Sample predictions with visual output

---

## 📂 Folder Structure

bash
📁 brain_tumor_detection/
├── brain_tumor_detection.ipynb
├── README.md
└── 📁 data/
    ├── yes/
    └── no/


📸 Sample Output
!img[alt]()
!img[alt]()
!img[alt]()

📈 Model Accuracy Plot
!img [alt]()

🏁 How to Run
Clone the repo
```
git clone https://github.com/yourusername/brain_tumor_detection.git
```
Navigate to project directory
 ``` cd brain_tumor_detection ```
 Install dependencies
 ``` pip install -r requirements.txt ``` 

 💡 Future Improvements
Add multiclass classification for tumor types

Use transfer learning (e.g., VGG16, ResNet50)

Integrate Flask app for real-time prediction

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

📬 Contact
Developed with ❤️ by Aman Saroj
