# 🧥 Invisible Cloak using OpenCV

Inspired by the magical world of **Harry Potter**, this project lets you experience a real-life simulation of the *Invisibility Cloak* using computer vision! With the help of **OpenCV** and a few lines of Python code, we make parts of your body covered with a red cloth appear invisible on screen.

## ✨ Project Overview

Have you ever imagined being invisible like Harry Potter? This project simulates the magical invisibility cloak using basic image processing techniques in OpenCV. By detecting a red-colored cloth and replacing it with a captured background, we can create a magical disappearing effect.

## 🎯 Algorithm

1. **Capture and store the background frame**
2. **Detect the red-colored cloth using HSV color segmentation**
3. **Create a mask to segment out the red region**
4. **Replace the red region in the video with the background**
5. **Display the final output with the invisibility effect**



## Requirements
To run this project, you'll need the following Python libraries:

- opencv
- numpy

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/farhat-1203/Invisible-Mirage.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Invisible-Mirage
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```


## 🗂️ Project Structure
```
Image-to-Sketch
├── harry_potter_cloak.py         # Main script for functioning
├── requirements.txt







