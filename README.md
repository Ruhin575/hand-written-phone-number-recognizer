
# Handwritten Phone Number Recognizer using CNN

This project demonstrates a robust digit classification system using a Convolutional Neural Network (CNN) trained on the MNIST dataset. The model is enhanced with custom Gaussian noise injection and data augmentation techniques to improve generalization, and is further extended to recognize full handwritten phone numbers.


## Features

- Built and trained a CNN model in Google Colab to classify digits (0–9) from grayscale images.
- Noise Injection: Gaussian noise added to half of the training and test images for robustness.
- Data Augmentation: Real-time shifts, zoom, and rotation applied using Keras’ ImageDataGenerator.
- Achieved:
  - Training Accuracy: 98.16%
  - Validation Accuracy: 99.37%
  - Test Accuracy: 99.48%
- Extended the model pipeline to:
  - Segment individual digits from images of full phone numbers.
  - Classify each digit using the trained CNN.
  - Reconstruct the complete phone number.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Google Colab

## Project Structure

handWritten_phoneNumber_recognizer.ipynb        - Colab notebook for model training and evaluation along with recognizing handwritten phone numbers   
-sample phone number images  
    └── phone_number_1.png  
    └── phone_number_2.png  
    └── phone_number_3.png  
README.md                         - Project documentation  

## Sample Output

Detected phone number: 9876543210


## How to Use

1. Clone or download the repository.
2. Open the notebook in Google Colab.
3. Run the recognition pipeline to get the predicted digits.
4. Upload an image of a handwritten phone number when prompted in cell 11.

