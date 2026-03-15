# GPU Accelerated Sobel Edge Detection using CUDA

## Overview

This project implements **Sobel Edge Detection** using:

* CPU (C++)
* GPU (CUDA)

It compares the performance between CPU and GPU implementations.

## Requirements

1. NVIDIA GPU
2. CUDA Toolkit installed
3. `nvcc` compiler
4. `g++`
5. 

## Execution 

Run CPU:
./cpu

<img width="220" height="52" alt="image" src="https://github.com/user-attachments/assets/dfd6abb2-c215-45dc-8bca-62ba0aca2547" />


Run GPU:
./gpu

<img width="191" height="51" alt="image" src="https://github.com/user-attachments/assets/810bf05b-fe21-4e00-ab4e-9aa40c029762" />


Expected Output:
Output edge image saved as output_cpu.pgm and output_gpu.pgm

<img width="1195" height="417" alt="Screenshot 2026-03-10 091349" src="https://github.com/user-attachments/assets/6fc3973e-90ce-4fdd-b6fb-86052fccc531" />

