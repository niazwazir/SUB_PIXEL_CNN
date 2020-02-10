# Super-resolution
This project implements the super resolution task as described in the paper "Real-Time Single Image and Video Super-Resolution Using an Efficient Sub-Pixel Convolutional Neural Network" using PyTorch. 

What is Super resolution? 
Super resolution is the process of upscaling and or improving the details within an image. Often a low resolution image is taken as an input and the same image is upscaled to a higher resolution, which is the output. The details in the high resolution output are filled in where the details are essentially unknown.

This repo includes the PyTorch implementation of the paper along with a sample result, a summary document and a pretrained model. It also has a onnx model called super_resolution.onnx which can be used to run the model for inference on CPUs with the help of 'Super_resolution_on_onnx_Runtime.ipynb' notebook. 

### Resources 
1. https://pytorch.org/tutorials/advanced/super_resolution_with_onnxruntime.html#running-the-model-on-an-image-using-onnx-runtime
2. https://pypi.org/project/onnxruntime/
