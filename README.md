# Deep-Learning-Powered-Facial-Recognition-on-Embedded-Systems
![Image](https://github.com/user-attachments/assets/76887e65-3612-4b19-8c18-ecedb04f221a)
![Image](https://github.com/user-attachments/assets/4a6486e6-dfbf-4b83-b675-f4285615611d)
![Image](https://github.com/user-attachments/assets/13a66bde-5eec-4bc0-99e6-aadd98f96c7d)
![Image](https://github.com/user-attachments/assets/996c862e-1a98-4852-939e-dc0905706008)

🚀 A Deep Learning-Based Facial Recognition Attendance System on STM32F7 Microcontroller

This project is the **second part** of my undergraduate capstone project (2023), focused on implementing an embedded system capable of facial recognition and interactive display, using **Convolutional Neural Networks (CNNs)** and the **STM32F7** platform.

---

## 💡 Project Overview

This smart attendance system combines **deep learning** and **embedded development** to identify individuals based on their facial features. It offers a standalone, low-power, and efficient attendance solution without relying on external computing systems.

---

## 🔧 Components and Tasks

### 🔹 Task 1: Facial Recognition using CNN
- A custom-trained CNN model capable of recognizing individual faces with high accuracy.
- Trained in Python using Keras/TensorFlow.
- The model is exported and optimized for embedded deployment using STM32Cube.AI.

### 🔹 Task 2: Message Display on STM32F7
- Displays real-time feedback such as "Welcome, Rania!" or "Access Denied" directly on the LCD screen.
- Interfaced with STM32's HAL libraries.

### 🔹 Task 3: Image Rendering on STM32F7
- Renders stored images of registered users for confirmation.
- Optimized bitmap display pipeline using DMA and SDRAM.

### 🔹 Task 4: Model Deployment with STM32Cube.AI
- The CNN model is quantized and converted into a C array.
- Integrated into STM32 IDE using STM32Cube.AI tools.
- Executed inference in real-time within the microcontroller.

---

## 🧠 Technologies Used

| Technology        | Purpose                          |
|-------------------|----------------------------------|
| Python (Keras)    | CNN model training               |
| STM32CubeIDE      | Embedded software development    |
| STM32Cube.AI      | AI model conversion and deployment |
| STM32F746G-DISCO  | Development board used           |
