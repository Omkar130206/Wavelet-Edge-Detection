# A Wavelet Approach for Edge Detection

## Mini Project – DTSP

This project implements edge detection using the **Discrete Wavelet Transform (DWT)**. The project was developed as a college group mini project for the ** DTSP** subject using Python and Google Colab.

## Project Objective

The objective of this project is to detect edges in an image using a wavelet-based approach. Wavelet transforms help analyze an image at different frequency levels and directions, making them useful for identifying image details and edges.

## Methodology

The following steps are used in this project:

1. Load the input image in grayscale.
2. Apply a 2D Discrete Wavelet Transform using the Haar wavelet.
3. Obtain the approximation and detail coefficients:

   * Horizontal detail coefficients
   * Vertical detail coefficients
   * Diagonal detail coefficients
4. Combine the detail coefficients to calculate the edge magnitude.
5. Normalize and display the detected edges.

## Technologies and Libraries Used

* Python
* Google Colab
* NumPy
* OpenCV
* PyWavelets
* Matplotlib

## Files

* `Edge_Detection.ipynb` – Python implementation of wavelet-based edge detection.
* `input.jpg` – Input image used for testing.
* `requirements.txt` – Required Python libraries.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open `Edge_Detection.ipynb` using Jupyter Notebook or Google Colab.
4. Make sure `input.jpg` is available in the same directory.
5. Run all the cells to view the input image and the wavelet edge detection output.

## Wavelet Used

This project uses the **Haar wavelet** for the 2D Discrete Wavelet Transform.

## Authors
This project was developed as a group mini project for the DTSP subject.
 1. Omkar Panchal 
 2. Ayush Pathade
 3. Yash Gosavi
 4. Kartik Kapse
College Group Mini Project – DTSP

