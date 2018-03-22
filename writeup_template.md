# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. 

1. I set a threshold,the pixel below the threshold will be (0,0,0)
2. I converted the images to grayscale
3. I use gaussian_blur to make the picture soft
4. I make a ROI to filter the useless picture
5. I use the houghlineP and draw_lines to get the line with the picture

If you'd like to include images to show how the pipeline works, here is how to include an image: 

![alt text](/Users/apple/Documents/Python/CarND-LaneLines-P1-master/result.jpg)


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when the lane is dashed


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to make the paramenter such as thresholod,min_line_len,max_line_gap be changing with the environment.




