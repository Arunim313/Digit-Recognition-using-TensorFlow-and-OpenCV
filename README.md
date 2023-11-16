# Digit Recognition using TensorFlow and OpenCV

This Python script demonstrates digit recognition using a TensorFlow model trained on the MNIST dataset. It utilizes a neural network built with TensorFlow and OpenCV for image handling.

## Requirements
- Python 3
- TensorFlow
- OpenCV
- NumPy
- Matplotlib

## Installation

1. Install the required libraries:
   ```bash
   pip install tensorflow opencv-python numpy matplotlib

1. Clone the repository or download the script.

# Usage
1. Run the script in a Python environment.


```bash
  python digit_recognition.py
```

2. The script will load the pre-trained model using the MNIST dataset and train it further if necessary. It then saves the model as digit_recognition.model.

3. It sequentially looks for image files named img{number}.png in the directory and attempts to predict the digits in those images using the trained model.

  - Ensure that the images to be predicted are in the same directory as the script.
  
  - The script will display the image, its filename, and the predicted digit using the trained model.

  - In case of an error in reading or processing the image, it will display 'Error'.
    
# Notes
  - The script uses TensorFlow's Sequential API to build a simple neural network architecture for digit recognition.

  - Training the model occurs using the MNIST dataset, normalizing the pixel values, and optimizing using the Adam optimizer.

  - Predictions are made on images (in PNG format) named img{number}.png found in the same directory as the script.

Feel free to modify the script or model architecture for different image recognition tasks or datasets.

