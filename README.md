# color-correction
This repository contains program for color correction of image using OpenCV

# Compile
g++ color-correct.cpp -o executable \`pkg-config --cflags --libs opencv\` -std=c++11

# Usage
./executable image_path output_path

# Example
./executable /home/2vin/myphoto.jpg  /home/2vin/output.jpg 
(Note: Substitute "/home/2vin/myphoto.jpg" by path of an existing image)

# Results
Input image    
![alt text](https://github.com/2vin/color-correction/blob/master/data/portrait.jpg)

Output Image    
![alt text](https://github.com/2vin/color-correction/blob/master/data/result.jpg)


