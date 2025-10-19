# 🧠 MNIST Digit Classifier (CNN + Streamlit)

A simple yet powerful **digit recognition app** built using **Convolutional Neural Networks (CNN)** trained on the **MNIST dataset**, and deployed using **Streamlit**.
You can **draw a digit (0–9)** on the canvas, and the model will predict it instantly!

---

## 🚀 Features

* 🖌️ Draw any digit (0–9) on screen
* 🤖 CNN-based prediction using TensorFlow/Keras
* ⚡ Real-time inference with Streamlit UI
* 💾 Model saved and loaded in `.keras` format
* 🌐 Ready for Streamlit Cloud deployment

---

## 🧩 Tech Stack

| Component      | Tool                              |
| -------------- | --------------------------------- |
| Model Training | TensorFlow / Keras                |
| Frontend UI    | Streamlit                         |
| Visualization  | Matplotlib                        |
| Dataset        | MNIST (70,000 handwritten digits) |

---

## 🏗️ Project Structure

```
├── model/
│   └── mnist_cnn_model.keras
├── main.py
├── requirements.txt
├── .streamlit/
│   └── config.toml
├── Notebook/
│   └── training_notebook.ipynb
├── test.py
└── README.md
```

---

## ⚙️ Installation & Run Locally

### 1️⃣ Clone the repo

```bash
git clone https://github.com/your-username/mnist-digit-classifier.git
cd mnist-digit-classifier
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Streamlit app

```bash
streamlit run main.py
```

### 4️⃣ Draw and predict!

A canvas will appear — draw a number (0–9), and the model will show its prediction.

---

## 🧠 Model Summary

| Layer     | Type               | Output Shape |
| --------- | ------------------ | ------------ |
| Conv2D    | Feature Extraction | (28,28,32)   |
| MaxPool2D | Downsampling       | (14,14,32)   |
| Conv2D    | Deep Features      | (14,14,64)   |
| Flatten   |                    | (12544)      |
| Dense     | Hidden Layer       | (128)        |
| Dense     | Output (Softmax)   | (10)         |

---

## 🌍 Deployment on Streamlit Cloud

1. Push all files to GitHub
2. Go to [streamlit.io/cloud](https://streamlit.io/cloud)
3. Connect repo → Select `main.py` → Deploy
4. Done! 🎉 Your app will be live in seconds.

---

## 🧾 Requirements

```
streamlit
tensorflow
numpy
matplotlib
streamlit-drawable-canvas
```

---

## ✨ Author

**👨‍💻 Maroof**
Python Developer | Machine Learning & Backend Enthusiast
🔗 GitHub: [maroof2424](https://github.com/maroof2424)

---
Chaho to main tujhe ek **beautiful README with emojis + preview screenshot** bana du (like GitHub project showcase style)?
Kya chahiyé minimalist ya fancy version?
