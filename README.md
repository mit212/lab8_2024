# Lab 8: Computer Vision

2.12/2.120 Intro to Robotics  
Spring 2024[^1]

<details>
  <summary>Table of Contents</summary>

- [0 (Prelab) Software Set Up](#0-prelab-software-set-up)
  - [0.1 Python](#01-python)
  - [0.2 OpenCV](#02-opencv)
  - [0.3 Matplotlib](#03-matplotlib)
- [1 Hardware Set Up](#1-hardware-set-up)
- [2 Gamma Adjustment](#2-gamma-adjustment)
- [6 Feedback Form](#6-feedback-form)

</details>

In this lab, you will be trying out different functions from OpenCV to visualize the computer vision techniques introduced in lecture.

## 0 (Prelab) Software Set Up
Estimated time of completion: 5 min

### 0.1 Python

You should already have Python (version 3.9+) installed from [Lab 4](https://github.com/mit212/lab4_2024?tab=readme-ov-file#01-python). You can check which version of Python you have by running `python3 -V` or `python -V` in your terminal.

### 0.2 OpenCV

OpenCV is an open source computer vision library. To install OpenCV, run `pip install opencv-python` in your terminal. 

### 0.3 Matplotlib

Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. To install Matplotlib, run `pip install matplotlib` in your terminal.

## 1 Hardware Set Up 

You will be using the built-in camera on your laptop. If your laptop does not have one, please ask the staff for an external camera.

Additionally, you should choose an object, preferably one of a solid color, to use for the
entire lab. Throughout the lab, we will attempt to separate that object in the images taken by
your camera from everything else.

## 2 Gamma Adjustment

In computer vision, one of the first things introduced is gamma adjustment or correction. To
experiment with this concept, open and run `gammaAdj.py`.

When you run this file, three windows will appear. One will show your unprocessed raw camera footage, another will show a processed (gamma adjusted image), and the last will have a slider. Play around with the slider and see what you observe (make it completely black or white).



## 6 Feedback Form

Before you leave, please fill out https://tinyurl.com/212-feedback. 

| :white_check_mark: CHECKOFF 3 :white_check_mark:   |
|:---------------------------------------------------|
| Show the feedback form completion screen to a TA or LA. |

[^1]: Version 1 - 2016: Peter Yu, Ryan Fish and Kamal Youcef-Toumi  
  Version 2 - 2017: Luke Roberto, Yingnan Cui, Steven Yeung and Kamal Youcef-Toumi  
  Version 3 - 2019: Jerry Ng, Jacob Guggenheim  
  Version 4 - 2020: Jerry Ng, Rachel Hoffman, Steven Yeung, and Kamal Youcef-Toumi  
  Version 4 - 2020: Phillip Daniel
  Version 5 - 2024: Jinger Chong, Josh Sohn