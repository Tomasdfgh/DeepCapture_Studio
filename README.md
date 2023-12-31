# DeepCapture Studio

## Introduction
Welcome to DeepCapture Studio, a software application designed to seamlessly integrate computer vision models into real-time webcam captures. Built using the powerful combination of Tkinter for the graphical user interface and PyTorch for deep learning capabilities, DeepCapture Studio brings an intuitive and interactive experience for users to upload their model and test its viability. DeepCapture is designed to complement AutoConvNet, an innovative software that enables the generation of CNN computer vision models without the need for coding. You can explore the capabilities of AutoConvNet, linked below, to effortlessly create diverse CNN models. DeepCapture serves as a testing ground where you can evaluate and interact with the models generated using AutoConvNet.

#### Executable Link:
DeepCapture Studio executable file: [[.exe link]](https://drive.google.com/file/d/186xQZR6iMpw77NV7w3b0u7U4JJcLmf0j/view?usp=sharing)

#### AutoConvNet Repository Link:
Repository Link: [[AutoConvNet]](https://github.com/Tomasdfgh/AutoConvNet)

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
  
4. **Real-Time Inference:** Once everything else is set up, DeepCapture Studio will return the output of the model once every .25 seconds.
   
   ![gif_before_reduced](https://github.com/Tomasdfgh/DeepCapture_Studio/assets/86145397/819b1e58-cd2f-4c97-a47a-3df6815ca5da)

    The GIF above is showing the data inference of a classification model that predicts numbers from grey scaled images that I have built using AutoConvNet. I will upload this model into this repository so you can play with it yourself.

5. **Display what the Model sees:** When the model has begin to infer data, you have the option to display what the model is seeing.

   ![image](https://github.com/Tomasdfgh/DeepCapture_Studio/assets/86145397/7de99391-005c-4033-ad87-7954952d32bf)
    After I have loaded up an age detection model that I have built using AutoConvNet, and the model has started inferring data, I can click on display image to see what the model is seeing as the image that it is passing in to get my age. 

## Target Audience:
DeepCapture Studio is ideal for developers, researchers, and enthusiasts looking to experiment with computer vision models in a practical, real-world setting. Whether you're exploring image classification or regression, DeepCapture Studio provides a user-friendly platform for seamless integration and immediate results.
