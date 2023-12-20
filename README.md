# BRISQUE Camera Quality Analyzer
Overview

The BRISQUE (Blind/Referenceless Image Spatial Quality Evaluator) Camera Quality Analyzer is a tool designed to assess the quality of images captured by different camera devices without the need for a reference image. This project uses the BRISQUE model to evaluate and score images in terms of their perceptual quality, providing valuable insights into the performance of various cameras and settings.
Features

    Image Quality Assessment: Evaluates the quality of images using the BRISQUE model.
    Camera Comparison: Compare the quality of images from different cameras.
    No Reference Needed: Performs blind/referenceless assessment, requiring no comparison to a reference image.
    User-Friendly Interface: Easy to use interface for uploading and analyzing images.
    Usage

To use BRISQUE Camera Quality Analyzer, follow these steps:

    Run the main script: Head to  Python->libsvm->python
    cd python
    make
and there you can run using python brisquequality.py <image_path>
    View the quality score and insights.
    
Some CLI results
![Screenshot from 2023-12-20 14-33-42](https://github.com/Sriaparna/OpenCV/assets/69186697/cf0e2af2-f1d1-44b8-943b-04f767c6b510)
![Screenshot from 2023-12-20 14-32-43](https://github.com/Sriaparna/OpenCV/assets/69186697/2f5c3c3b-d3d0-4b66-9b65-860bb60129e4)



How It Works

    The tool analyzes the input image using the BRISQUE algorithm.
    It computes a score representing the quality of the image. Lower scores indicate higher quality.
    The algorithm considers various factors like texture, noise, and sharpness to evaluate image quality.
    For now, it is a CLI, but can be embedded with real time use cases like running the script for cameras and finding the quality of the camera
  # Mainly useful for applications where camera is fitted in mud/dusty areas!!
