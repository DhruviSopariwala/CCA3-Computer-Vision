# CCA 3 – Computer Vision Practical Assignment

## Project Overview

This project demonstrates image restoration, image segmentation, feature extraction, and object recognition using Python.

The assignment is implemented using Jupyter Notebook.

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-image
- Ultralytics YOLO
- Pandas

## Task 1: Image Restoration and Segmentation

Implemented techniques:

- Gaussian Noise
- Salt-and-Pepper Noise
- Median Filtering
- Gaussian Filtering
- PSNR and SSIM
- Binary Thresholding
- Erosion, Dilation, Opening and Closing
- Canny Edge Detection
- Watershed Segmentation

## Task 2: Feature Extraction and Image Matching

Implemented techniques:

- Histogram of Oriented Gradients (HOG)
- SIFT Keypoint Detection
- SIFT Descriptors
- SIFT Feature Matching
- Feature Matching After Rotation
- Feature Matching After Resizing

### Results

| Experiment | Good SIFT Matches |
|---|---:|
| Original Photographs | 109 |
| After Rotation | 105 |
| After Resizing | 112 |

## Task 3: Object Recognition

Implemented techniques:

- Viola–Jones Face Detection using Haar Cascade
- YOLO Object Detection
- Bounding Box Visualization
- Detection Comparison

### Results

- Viola–Jones detected 1 face.
- YOLO detected 1 person with a confidence score of 0.89.

## How to Run

1. Download or clone the repository.
2. Install the required libraries:

   `pip install -r requirements.txt`

3. Create an `inputs` folder and place your original images inside it as `photo1.jpg` and `photo2.jpg`.
4. Open the Jupyter Notebook files.
5. Run the cells in sequence.
6. View generated results in the `outputs` folder.

## Dataset

Original photographs captured for the assignment are used for image processing and detection experiments. Input photographs are supplied separately when required.

## Project Explanation Video

A project explanation video has been recorded to demonstrate the Computer Vision assignment implemented using Python and Jupyter Notebook.

The video covers:
- Task 1: Image Restoration and Segmentation
- Task 2: Feature Extraction and Image Matching
- Task 3: Object Recognition using Viola–Jones and YOLO

**[Watch Project Explanation Video on Loom](https://www.loom.com/share/8d5dab652ccc439ea4a1f745e879ebcb)**

## Conclusion

The project demonstrates the practical application of image-processing and computer-vision algorithms using Python. The techniques were compared using visual results, image-quality measurements, feature matching and object detection.
