# 🖼️ AI Image Classifier

## 🚀 Overview
As part of my journey learning **AI engineering**, I built an AI image classification web application using **Python, Streamlit, and TensorFlow**, powered by the **MobileNetV2** deep learning model.

The application allows a user to **upload an image**, and the AI predicts what object is present in the image. The model returns the **top predictions with confidence scores**.

---

## 🧠 Features
✅ Upload an image through a simple web interface  
✅ AI predicts what object is in the image  
✅ Displays the **top 3 predictions** with confidence scores  
✅ Fast and lightweight model using **MobileNetV2**  - a model that is already trained.
✅ Clean **Streamlit UI**

---

## 🖥️ Application Interface

![ui](https://github.com/user-attachments/assets/7846e87d-2cec-4946-b63b-881fc37a7f17)

---

## 🛠️ Tech Stack
- 🐍 Python  
- ⚡ Streamlit  
- 🧠 TensorFlow / Keras  
- 📷 OpenCV  
- 🔢 NumPy  
- 🖼️ Pillow  

---

## ⚙️ How It Works
1️⃣ The user uploads an image using the Streamlit interface.  
2️⃣ The image is converted into a **NumPy array** and resized to **224x224 pixels**.  
3️⃣ The image is **preprocessed** to match the format expected by MobileNetV2.  
4️⃣ The pretrained **MobileNetV2 model** performs inference on the image.  
5️⃣ The model returns the **top predictions with confidence scores**.

---

## 📦 Installation

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Streamlit app:

```bash
streamlit run main.py
```

Then open the local web interface in your browser to upload and classify images.

---

## 🎯 Learning Goal
This project was built as part of my **AI engineering learning journey** to understand how pretrained deep learning models can be integrated into real-world applications.

---

## 📂 Project Structure

```
ai-image-classifier
│
├── main.py
├── requirements.txt
├── pyproject.toml
└── README.md
```

---

## 🙌 Author
Built by **Ilyas** as part of learning **AI Engineering and Machine Learning applications**.
