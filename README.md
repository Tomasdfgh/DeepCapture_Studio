# Deep Capture Studio

## Introduction
Welcome to Deep Capture Studio, a software application designed to seamlessly integrate computer vision models into real-time webcam captures. Built using the powerful combination of Tkinter for the graphical user interface and PyTorch for deep learning capabilities, Deep Capture Studio brings an intuitive and interactive experience for users to upload their model and test its viability.

#### Executable Link:
DeepCapture Studio executable file: [link]

#### Framework and Libraries Used:
- tkinter: GUI toolkit for creating windows and interactive elements.
- cv2: Library for image processing and webcam operations.
- Torch and Torchvision: PyTorch for image processing and webcam operations.
- PIL: Libraries for image handling and conversion.
- Matplotlib: Library for creating visualizations and plots.
- NumPy: Library for numerical opertaions and array handling.
- Base64 and BytesIO: Handling binary data, especially for Tkinter.

## Key Features:
- **Live Webcam Interaction:** Capture and process real-time webcam footage with ease.
- **Torch Model Integration:** Utilize PyTorch to seamlessly integrate pre-trained models for image classification or regression tasks.
- **User-Friendly Interface:** An intuitive Tkinter-based interface ensures a smooth user experience, making it accessible for both beginnners and experienced users.
- **Dynamic Configurability:** Adjust image dimensions and model type on-the-fly to tailor the application to specific use cases.

## **How it Works:**
1. **Load Model:** Load your PyTorch TorchScript Trace model using the straightforward interface.
2. **Choose Model Type:** Choose your model type, either a classification or regression model.
3. **Configure Dimensions:** Dynamically set image dimensions and number of channels that the model accepts.
4. **Real-Time Inference:** Once everything else is set up, Deep Capture Studio will return the output of the model once every .25 seconds.

## Target Audience:
Deep Capture Studio is ideal for developers, researchers, and enthusiasts looking to experiment with computer vision models in a practical, real-world setting. Whether you're exploring image classification or regression, Deep Capture Studio provides a user-friendly platform for seamless integration and immediate results.
