# ** Deep Fake Image Detection using Deep Learning**  

## **📌 Project Overview**  
This project aims to classify images as **real or fake** using a **Convolutional Neural Network (CNN)**. The model is trained on a dataset containing authentic and manipulated images to detect **forgeries, AI-generated images, and edited photos**.  

The project is implemented using **Python, TensorFlow, Keras, OpenCV, and NumPy** and can be run on **Google Colab**.

---

## **📂 Dataset**  
The dataset consists of:
✅ **Real Images** – Authentic, unaltered images.  
✅ **Fake Images** – AI-generated, deepfake, or manipulated images.  

Images are preprocessed to match the model input size and normalized for better performance.

---

## **📌 Model Architecture**  
The CNN model consists of:  
✔ **3 Convolutional Layers** with ReLU activation  
✔ **Batch Normalization & MaxPooling**  
✔ **Flatten Layer**  
✔ **Dense Layers** with Dropout (to prevent overfitting)  
✔ **Sigmoid Activation** (for binary classification)  

The model outputs a **probability (0 or 1)**, which is converted into a **binary classification (Real or Fake)**.

---

## **📊 Model Training & Evaluation**  
The model is trained using:  
✅ **Binary Crossentropy Loss** (since it’s a binary classification task)  
✅ **Adam Optimizer** (for efficient learning)  
✅ **Augmented Data** (rotation, flipping, etc.)  
✅ **Early Stopping** (to prevent overfitting)  

After training, the model achieves **high accuracy** in distinguishing real and fake images.

---

## **🖥️ Running the Model in Google Colab**  
You can try the model **directly in Google Colab** using the notebook created by **Thulasi Sandeep Chemukula**.  



---

## **📌 How to Use**  
1️⃣ Upload an image to Colab.  
2️⃣ The model processes the image and predicts whether it’s **Real** or **Fake**.  
3️⃣ The result is displayed with the image and prediction label.

---

## **🚀 Technologies Used**  
✔ **Python**  
✔ **TensorFlow / Keras**  
✔ **OpenCV**  
✔ **NumPy & Pandas**  
✔ **Matplotlib**  

---

## **📌 How to Run Locally**  
```bash
# Clone the repository
git clone https://github.com/yourusername/Fake-Image-Detection.git
cd Fake-Image-Detection

# Install dependencies
pip install -r requirements.txt

# Run prediction on a test image
python predict.py --image test.jpg
```

---

## **🔗 Credits**  
🔹 **Author:** Thulasi Sandeep Chemukula  
🔹 **Contributors:** Mohith Sai Balaji 
🔹 **GitHub Repository:** [Fake Image Detection](https://github.com/THULASISANDEEP/Fake-Image-Detection)  

---

✅ **This README provides a detailed explanation of your project with a Colab link and proper documentation.** 🚀 Let me know if you need modifications! 🎯
