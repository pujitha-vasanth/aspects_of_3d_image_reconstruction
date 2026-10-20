# Aspects of 3D Image Reconstruction

Two small experiments on recovering 3D information from a single 2D image.

1. **Depth map:** a small convolutional network in TensorFlow/Keras trained on one image, producing a per-pixel depth-style map
2. **Surface from shading:** Sobel gradients on a grayscale image, turned into surface normals, then integrated into an estimated 3D surface and plotted

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pujitha-vasanth/aspects_of_3d_image_reconstruction/blob/main/2D_to_3D_image_reconstruction.ipynb)

The notebook asks you to upload your own image when run in Colab.

## Stack

Python, TensorFlow/Keras, OpenCV, NumPy, Matplotlib
