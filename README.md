## CUDA GPU Image Processing
GPU-accelerated RGB to Grayscale image processing using CUDA.

## Results
GPU: NVIDIA L4
Input images: 100
Image size: 256x256
Output images: 100
Total GPU kernel time: 0.878 ms
Average GPU kernel time: 0.009 ms/image

## Run
```
nvcc image_processing.cu -o image_processing
./image_processing
```
