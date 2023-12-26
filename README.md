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
  ![image](https://github.com/Tomasdfgh/DeepCapture_Studio/assets/86145397/a410df7c-a759-4c58-80a5-d495370713dd)

    You can load the model using the load model button, only torchscript models (.pt) are accepted. If you haven't load any models yet the notification on the bottom right will let you know.

2. **Choose Model Type:** Choose your model type, either a classification or regression model.
  ![image](https://github.com/Tomasdfgh/DeepCapture_Studio/assets/86145397/2295a5aa-be43-45e3-9b92-21dae071216d)

    After you have loaded the model, you can select the model type. Either regression or classifcation. If you have have not done this step yet, the notification on the bottom right will inform you so. 

3. **Configure Dimensions:** Dynamically set image dimensions and number of channels that the model accepts.
  ![image](https://github.com/Tomasdfgh/DeepCapture_Studio/assets/86145397/dead6d98-3004-4af2-a3ae-4c35630b579c)

    Once this step is done and correctly configured, the model will begin to infer data. If you have incorrectly indentified anything, DeepCapture will let you know. It is also noteoworthy that if you trained your model on all grey scaled images (channel size of 1), DeepCapture will automatically greyscale the feed that is being passed into the model as well.
  
4. **Real-Time Inference:** Once everything else is set up, Deep Capture Studio will return the output of the model once every .25 seconds.

## Target Audience:
Deep Capture Studio is ideal for developers, researchers, and enthusiasts looking to experiment with computer vision models in a practical, real-world setting. Whether you're exploring image classification or regression, Deep Capture Studio provides a user-friendly platform for seamless integration and immediate results.
