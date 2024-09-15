![Logo](https://github.com/AKGanesh/ImageOperations/blob/main/opencv_lady.png)

# Operations on an image using OpenCV

This Python project, using OpenCV, provides guidance for performing various image processing operations on a portrait of a lady. 

The available operations include:
- Contrast enhancement: Adjusting the contrast of the image to make details more visible.
- Mask extraction: Isolating the lady's figure from the background using thresholding and morphological operations.
- Edge detection: Identifying the boundaries of the lady's figure using morphological operations and Canny edge detection.

## Implementation Details

- Dataset: Image of portrait lady
- Model: NA
- Input: Image of portrait lady
- Output: Modified images (Contrast, Mask, Morph, Segment)

## Process
- Choose the operation that needs to be performed like masking, edge detection etc. Follow the appropriate procedure/documentation to obtain the result.

## Libraries

**Language:** Python,

**Packages:** OpenCV2, Numpy, Matplotlib

## Roadmap

- To experiment with matting, semantic segmentation, stiching and augmentation

## FAQ

#### Whats is OpenCV?
- OpenCV (Open Source Computer Vision Library) is a powerful open-source library for computer vision, machine learning, and image processing. It provides a vast collection of functions and algorithms that can be used to perform various tasks related to images and videos
https://opencv.org/


#### What is a this space conversion RGB -> HSG?
- If you're working with images in OpenCV, they are typically represented in RGB format by default. You can check the image's color space using the cv2.cvtColor() function to convert it to another color space like HSV or grayscale. Converting BGR to HSV can provide advantages in terms of color manipulation, segmentation, human perception, and algorithm optimization. It's a common step in many image processing pipelines, especially when dealing with color-related tasks.


#### What are various operations that can performed?
- Morphological operations are useful for analyzing and modifying image shapes.
- Image masking and segmentation are essential for isolating objects.
- Edge detection helps identify object boundaries.

#### What are Morphological operations?
- Morphological operations are a set of techniques used in image processing to analyze and modify the shape and structure of objects within an image. They involve applying a structuring element (a small matrix) to the image and performing operations based on the interaction between the structuring element and the image pixels. Please refer to Erosion, Dilation, Opening and Closing etc.,

#### What is image masking?
- Image masking is a fundamental technique in image processing that allows you to focus on specific regions of an image and perform operations on those regions independently.

#### What is GrabCut?
- GrabCut is a powerful interactive segmentation algorithm that can be used to accurately extract objects from images. It's a valuable tool for various computer vision applications.  It combines graph cuts with iterative Gaussian mixture models to achieve accurate foreground-background separation.

## Acknowledgements

- https://opencv.org/
- https://docs.opencv.org/3.4/d8/d83/tutorial_py_grabcut.html
- https://docs.opencv.org/3.4/da/d22/tutorial_py_canny.html


## Contact

For any queries, please send an email (id on github profile)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)