# Drone-Delivery-System
This repository contains code of all the tasks concerning the Summer Research Project of "Drone Delivery Systems.
Real-Time Gesture or Action Recognition
--Takes several frames as input (30 videos consisting 30 frames each frame converted to an array of 1662 values for all 3 classes/actions (i.e. drone left, drone right, drone stable))
--Mediapipe holistics used for collecting those 1662 key points(saved as NumPy arrays)
--Using TensorFlow to build an LSTM model
--Making predictions in Real-Time using OpenCV
--Achieved a testing accuracy of 80%(could be increased to 90%)
Using LSTM over CNN as -
-Smaller Dataset is sufficient 
-0.5 Million parameters compared to 30 Million
-Faster Predictions

". 
![drone_output_2](https://user-images.githubusercontent.com/80156877/200922584-c66acd0a-43e8-4f55-91b2-9e13e6460e2a.png)
![drone_output](https://user-images.githubusercontent.com/80156877/200922601-8cb8ddac-a18f-4355-b8d5-d3b4ffdc999b.png)
![accuracy](https://user-images.githubusercontent.com/80156877/200922664-9321b3fb-d14d-4e23-bdaa-6ba43ca14b97.png)
