# 💅 KukuKu – Nail Diseases Detection App

## Our Logo Apps
<p align="center">
  <img src="./Image/logo_KukuKu.png">
</p>

KukuKu is a machine learning–based application designed to detect nail diseases from nail images, helping users recognize potential nail health issues early.

---

## 📌 Project Details
Disease detection based on nail conditions is a machine learning project to create a model that can detect types of disease symptoms based on nail images. Self-awareness about health is often ignored by society. Most people don’t have self awareness that something as insignificant as a nail may indicate something more serious. Nail diseases are very common and may be left unnoticed until serious health impacts start to appear. This app will provide a convenient and easily accessible solution for detection of nail disease. For this project, we will use an already available dataset on nail diseases provided here (https://universe.roboflow.com/knm/nail-disease-detection-mxoqy/). At the training stage, our model is trained using a dataset consisting of 6363 nail images, with 9 classes of disease types which will then be processed to create a model. Then we will evaluate the performance of the model to find out whether the model created has good accuracy in all types of classes. The results of this model will then be integrated into a mobile application which will be easy for users to use. This application will help to take pictures and analyze the user's nail images. That way, our model can provide information in early detection of disease based on the condition of their nails.

---

## 🎯 Objectives
- Detect potential nail diseases from nail images
- Apply machine learning for image-based disease classification
- Support early awareness of nail health conditions

---

## 🛠️ Tools
 ![](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![](https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white) 
 ![](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) ![](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) 
 ![](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white) ![](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white) 

---

## 📊 Road Map
1. Machine Learning part: On the part of the machine learning team, our role in the nail health detection project is primarily to create a machine learning model that can detect both healthy and unhealthy nails. The machine learning team will create the detection model using the convolutional neural network (CNN) algorithm and then we will deploy it using Tensorflow lite.

2. Cloud Computing part: The backend/cloud part of the project involves creating a Cloud Storage bucket for image storage and creating endpoint routes using either NodeJS hapi-server or Python Flask. After local testing, a Docker configuration will be created and Cloud Build will be used to containerize the application and upload it to the Container Registry. Finally, the container will be deployed on Cloud Run for public access.

3. Mobile Development part: The backend/cloud part of the project involves creating a Cloud Storage bucket for image storage and creating endpoint routes using either NodeJS hapi-server or Python Flask. After local testing, a Docker configuration will be created and Cloud Build will be used to containerize the application and upload it to the Container Registry. Finally, the container will be deployed on Cloud Run for public access.

---

## 📂 Project Structure
```text
KukuKu/
│── data/              # Dataset (images)
│── notebooks/         # Google Colab
│── models/            # Trained models
│── src/               # Source code
│── results/           # Visualizations & outputs
│── README.md
