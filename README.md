# Computer Vision: Multi-Object Detection with Haar Cascades

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1G0cG7aPLt1Qov-iO0z3YqAodlRGMxDTa?usp=sharing)

## 📌 Project Overview
This repository showcases the implementation of **Computer Vision** techniques for detecting human faces, eyes, and vehicles. Developed as part of my advanced studies in **Informatics Engineering at the Polytechnic Institute of Bragança (IPB)**, the project explores the practical application of **Haar Cascade Classifiers** to identify specific patterns in complex visual environments.

## 🚀 Key Features
* **Face Detection**: Utilizes `haarcascade_frontalface_default.xml` with fine-tuned `scaleFactor` and `minNeighbors` to locate human faces in varied group settings.
* **Ocular Recognition**: Identifies human eyes within detected face regions using the `haarcascade_eye.xml` classifier.
* **Vehicle Tracking**: Detects cars in urban imagery by optimizing `detectMultiScale` parameters for specific object sizes and scales.
* **Image Preprocessing**: Implements grayscale conversion and resizing techniques to optimize computational efficiency for real-time inference.

## 🛠️ Tech Stack
* **Language**: Python
* **Primary Library**: OpenCV (`cv2`)
* **Platform**: Google Colab
* **Algorithms**: Haar Cascade Classifiers (Viola-Jones Framework)

## 📊 Technical Insights
The project demonstrates proficiency in parameter tuning for Computer Vision models:
* **Scaling Control**: Precise adjustment of `scaleFactor` (e.g., 1.3 for faces or 1.008 for vehicles) to balance detection sensitivity and accuracy.
* **Noise Reduction**: Implementation of `minNeighbors` and `minSize`/`maxSize` constraints to eliminate false positives in cluttered images.

## 📂 Repository Structure
* `ReconecimentoDeFaces.ipynb`: Full implementation of image processing and detection logic.
* `Images/`: Sample datasets including group photos and urban traffic scenes.
* `Cascades/`: XML files containing the pre-trained Haar Cascade features.

---

## 👤 About the Author
**Pedro Ferreira Franco**
Developer & Professor | MSc Student in Informatics Engineering at **IPB** 🇵🇹

I am a software developer and triathlete with a passion for Robotics, IoT, and Artificial Intelligence. Currently researching AI-driven calibration for industrial robots at the **Polytechnic Institute of Bragança**.

🔗 **Connect with me:**
* **LinkedIn**: [pedro-ferreira-franco](https://www.linkedin.com/in/pedro-ferreira-franco/)
* **GitHub**: [PedroFerreiraFranco](https://github.com/PedroFerreiraFranco)
* **Instagram**: [@pedrofranco_11](https://www.instagram.com/pedrofranco_11/)

---
*Developed in Bragança, Portugal.*
