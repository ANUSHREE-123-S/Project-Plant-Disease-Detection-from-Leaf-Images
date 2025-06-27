# Project-Plant-Disease-Detection-from-Leaf-Images
#  Plant Disease Detection Using CNN

This is a mini project that detects plant leaf diseases using a trained Convolutional Neural Network (CNN) model. It includes a simple and user-friendly web interface created with Streamlit.



 Features

-  Upload a leaf image (JPG/PNG)
-  Predicts the disease using a trained CNN model
-  Displays confidence score
-  Streamlit-based web application



 Dataset

We used a subset of the PlantVillage dataset containing *6 classes*:

- Tomato___Healthy  
- Tomato___Early_blight  
- Tomato___Late_blight  
- Potato___Early_blight  
- Potato___Late_blight  
- Pepper,bell__Bacterial_spot  

 Dataset Source: [PlantVillage - Kaggle](https://www.kaggle.com/datasets/emmarex/plantdisease)


 Technologies Used

- Python 3.10  
- TensorFlow / Keras  
- Streamlit  
- OpenCV  
- NumPy  
- Pillow  

Model Details

Image size: 128x128

CNN Layers: Conv2D → MaxPooling → Flatten → Dense

Final Layer: Softmax for multiclass classification

Optimizer: Adam

Loss: Categorical Crossentropy

Epochs: 10




 Sample Output

 Predicted Disease: Tomato___Early_blight

 Confidence: 96.3%
