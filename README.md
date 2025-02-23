**Driver Drowsiness Detection Using CNN**

A deep learning system that detects driver drowsiness in real-time using Convolutional Neural Networks (CNN). This project aims to enhance road safety by identifying signs of driver fatigue and alerting users before potential accidents occur.

**Overview:**
This system uses computer vision and deep learning techniques to analyze driver facial expressions and detect drowsiness with high accuracy. The model achieved 99.93% accuracy on the test dataset, making it suitable for real-world applications in vehicle safety systems.

**Features:**

- Real-time drowsiness detection using CNN
- Binary classification (Drowsy/Non-drowsy)
- High accuracy and low false-positive rate
- Optimized for edge deployment in vehicles
- Support for various input image conditions

**Technical Architecture**
The CNN model consists of:

- Three convolutional layers with 3x3 filters
- Max pooling layers (2x2 windows)
- Dropout layer (0.5) for preventing overfitting
- ReLU activation in hidden layers
- Sigmoid activation for final classification
- Binary Cross-Entropy loss function
- Adam optimizer with learning rate 1e-4

**Dataset:**
The model was trained on the Driver Drowsiness Dataset from Kaggle, containing

- Total images: 41,700
- Drowsy images: 22,300
- Non-drowsy images: 19,400
- Image size: 64x64 pixels (after preprocessing)
