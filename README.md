# Lane_Detection
Lane Detection Project for Udacity self driving car nanodegree.




https://github.com/dinaashraf20003/Lane_Detection/assets/73821958/092f6d11-a18a-4536-b88a-4b1f41ebbd44




# Pipeline 
- Converted the images to grayscale.
- Apply gaussian blur.
- Edge Detection using Canny.
- Define vertices of four sided polygon mask.
- Apply Hough Transform. 

# Used Libraries
- Python 3.9
- opencv
- numpy
- matplotlib
- moviepy

# Additional Scripts
## Color selection
- Function: Detect lanes using color selection method using thershold for RGB Parameters.
![Figure_1](https://github.com/dinaashraf20003/Lane_Detection/assets/73821958/b52e6373-6090-4ce7-9819-8e545a3f92e8)
## Region Masking and Combine color mask
- Function: Add a criterion to only consider pixels for color selection in the region where we expect to find the lane lines. 
![Figure_2](https://github.com/dinaashraf20003/Lane_Detection/assets/73821958/7fc7f0d6-8fd6-4e9e-a0f3-06577d2db479)
![Figure_3](https://github.com/dinaashraf20003/Lane_Detection/assets/73821958/d5aa6dda-ba94-4221-b9c5-29bd0c2322dd)

## Canny edge detection 
- Function: Find edges by looking for strong gradient, i.e. very
different values between adjacent pixels.
![Figure_4](https://github.com/dinaashraf20003/Lane_Detection/assets/73821958/6cbbca32-652b-43f8-a578-a7789a78f57a)

## Hough Transform 
- Function: A line in image space can be represented as a single point in parameter space, or Hough Space then the detected lines are highlighted on the image.
![Figure_5](https://github.com/dinaashraf20003/Lane_Detection/assets/73821958/80e4c132-ada0-4a75-93a6-1b8595486898)


