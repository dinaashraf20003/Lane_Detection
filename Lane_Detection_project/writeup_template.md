# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.png "Grayscale"
[image1]: ./examples/edge_detection.png "Edge_Detection"
[image1]: ./test_images_output/image.png "Output"
---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I apply gaussian blur. Then edge detection using canny. Affterwards define vertices of four sided polygon mask. THe Hough transorfm is applied.


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when the car moves near an object(wall, car) 

Another shortcoming could be if the car moves faster.


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to tune parameters.

