# Drone Delivery Systems - Real-Time Gesture or Action Recognition
This repository contains the code for the Summer Research Project on "Drone Delivery Systems" related to Real-Time Gesture or Action Recognition.

## Overview
The goal of this project is to recognize and classify gestures or actions in real-time using a deep learning model. The project involves the following tasks:

### Collecting input frames:
The system takes several frames as input, where each frame is a video consisting of 30 frames. Each frame is converted into an array of 1662 values, representing the key points of the gestures or actions (i.e., drone left, drone right, drone stable).

### Data collection:
Mediapipe Holistics is used to collect the 1662 key points from the input frames. These key points are then saved as NumPy arrays for further processing.

### Model development:
TensorFlow is used to build an LSTM (Long Short-Term Memory) model.

LSTM is chosen over CNN (Convolutional Neural Network) due to the following advantages:

-Smaller dataset requirement
-Significantly fewer parameters (0.5 Million compared to 30 Million in CNN)
-Faster predictions
Real-time prediction: OpenCV is utilized to make predictions in real-time. The trained LSTM model is used to classify the gestures or actions captured from the live video feed.

## Accuracy and improvement: The model achieved a testing accuracy of more than 80%, with potential for further improvement up to 90%.

## Getting Started
To run the code and reproduce the results, follow these steps:

Clone the repository: git clone https://github.com/[your-username]/drone-gesture-recognition.git
Install the required dependencies: using the pip install cell of the notebook
Collect the input frames using the Mediapipe Holistics library and save them as NumPy arrays.
Train the LSTM model using the collected data.
Run the real-time prediction script using OpenCV.
Feel free to explore the code and modify it according to your requirements.

## Contributing
If you would like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch: git checkout -b feature/my-feature.
Make your changes and commit them: git commit -m 'Add some feature'.
Push to the branch: git push origin feature/my-feature.
Submit a pull request.
Your contributions are highly appreciated!

## License
This project is licensed under the MIT License.

## Acknowledgments
We would like to express our gratitude to the mentors and contributors for their guidance and support throughout this project.

If you have any questions or suggestions, please feel free to contact us.

". 
![drone_output_2](https://user-images.githubusercontent.com/80156877/200922584-c66acd0a-43e8-4f55-91b2-9e13e6460e2a.png)
![drone_output](https://user-images.githubusercontent.com/80156877/200922601-8cb8ddac-a18f-4355-b8d5-d3b4ffdc999b.png)
![accuracy](https://user-images.githubusercontent.com/80156877/200922664-9321b3fb-d14d-4e23-bdaa-6ba43ca14b97.png)
