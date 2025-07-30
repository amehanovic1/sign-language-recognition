# Sign Language Recognition System  

Implemented during the **Pattern Recognition and Image Processing** course at the Faculty of Electrical Engineering, University of Sarajevo. The system uses a CNN model trained on the Sign Language MNIST dataset to recognize hand gestures in real time via webcam.

---

## Usage Instructions

1. **Model Training**  
   Train the CNN model on the Sign Language MNIST dataset

2. **Running Real-Time Recognition**  
   Run the Python script which:  
   - Opens the webcam and displays the video stream.  
   - Defines a rectangle area for focused recognition.  
   - Preprocesses the region of interest (ROI) using the same steps as training images (scaling, grayscale, resizing).  
   - Predicts the sign class using the loaded CNN model.  
   - Displays the predicted class live on the video window.  
   - Allows exiting the program by pressing the `q` key.

---

## Code Structure

- **Model training and evaluation:** CNN architecture with BatchNormalization, Conv2D, MaxPooling2D, Dropout, Flatten, and Dense layers.  
- **Model serialization:** Saving and loading the model using `pickle`.  
- **Real-time inference:** Script for detecting and classifying signs from the video stream.

---


https://github.com/amehanovic1/sign-language-recognition/assets/125169959/109cf517-dd46-44d9-9d35-45efed98958f


