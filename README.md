# 🧑‍💻 **Face Recognition System **

## 📌 **Project Description**

A Python-based **real-time face recognition system** developed using **OpenCV** and **NumPy**.  
This project includes face detection, training, and recognition modules using **Haar Cascades** and **LBPH (Local Binary Patterns Histograms) algorithm**, making it suitable for security, authentication, and monitoring systems.

## 🚀 **Features**

- 📷 **Real-time face detection** using webcam  
- 🧠 **Face recognition** using LBPH algorithm  
- 📁 **Automatic dataset generation** for multiple users  
- 📊 **Model training and saving** for future use  
- 👤 **Multiple user support** with unique IDs  
- 💻 **Easy-to-use interface** with minimal setup  
- ⚡ **High accuracy** and fast processing  
- 🔄 **Retraining capability** for new users 

## 🛠️ **Technologies Used**

**Python 3.8+** -  Core programming language     
**OpenCV** - Computer vision and image processing   
**NumPy** - Numerical operations and array handling   
**Haar Cascade Classifier** - Face detection algorithm   
**LBPH Face Recognizer** - Face recognition algorithm      

## ⚙️ **Installation**

### 1️⃣ Clone the Repository

```
git clone https://github.com/himalibarde/Face_Recognition.git
cd FaceRecognition
```

### 2️⃣ Install Required Libraries

```
pip install -r requirements.txt
```

**Or install manually:**

```
pip install opencv-python
pip install opencv-contrib-python
pip install numpy
```

### 3️⃣ Download Haar Cascade File

The Haar Cascade XML file is usually included, but if missing, download it from:
[Haar Cascade Frontal Face](https://github.com/opencv/opencv/tree/master/data/haarcascades)

(Download it in Project folder)

## 🎮 **Usage**

### **Step 1: Create Dataset (Face Detection)**

Run the face detection script to capture face images:

```
python 01_face_dataset.py
```

- Enter a **User Name** 
- The script will capture **50-100 images** of your face
- Images will be saved in the `dataset/` folder
- Press **'esc'** to stop capturing early

### **Step 2: Train the Model**

Train the face recognition model using captured images:

```
python 02_face_training.py
```

- The script processes all images in `dataset/`
- Generates a `trainer.yml` file in the `trainer/` folder
- Shows training progress in the console

### **Step 3: Recognize Faces**

Run the face recognition script:

```
python 03_face_recognition.py
```

- The webcam will start
- Detected faces will be recognized with **User Name** and **confidence level**
- Press **'esc'** to quit

## 👨‍💻 **Author**

**Himali Barde**

- GitHub: https://github.com/himalibarde
- LinkedIn: www.linkedin.com/in/himali-barde-5b4b1a34a
- Email: himalibarde859@gmail.com

