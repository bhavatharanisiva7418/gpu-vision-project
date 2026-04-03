# gpu-vision-project

# GPU Accelerated Image Processing using CUDA (Colab + CuPy)
## Aim
To implement image processing techniques using GPU acceleration and compare the performance with CPU execution.



## Description
This project demonstrates how GPU computing can speed up image processing tasks. 
An image is processed using both CPU and GPU, and the execution time is compared. 
CuPy is used to perform operations on the GPU using CUDA.


## ⚙️eps

1. Upload the input image  
2. Load the image using OpenCV  
3. Convert image to GPU array using CuPy  
4. Apply blur filter using:
   - CPU (OpenCV)
   - GPU (CuPy convolution)  
5. Perform edge detection (optional)  
6. Measure execution time for both CPU and GPU  
7. Save output images  



## Output

# original image
 
 <img width="386" height="300" alt="image" src="https://github.com/user-attachments/assets/8d93c0a0-6e0b-41f0-9271-428ac321fcf8" />

## cpu vs gpu

<img width="832" height="364" alt="image" src="https://github.com/user-attachments/assets/2fe0cdff-ba17-4028-891f-6a012473eed9" />



## Result

The GPU implementation is faster than the CPU implementation due to parallel processing.  
This shows that GPU computing is efficient for large-scale image processing tasks.



