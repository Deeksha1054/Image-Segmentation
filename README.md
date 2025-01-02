# Image Clustering with K-Means

This project demonstrates image clustering using K-Means for different values of \(k\), including \(k=2\), \(k=3\), and \(k=9\). The process includes preprocessing the image to grayscale before clustering and visualizing the clustered results.

## Overview

Clustering groups similar pixels of an image into distinct clusters based on their features, such as color or intensity. The value \(k\) determines the number of clusters, and each pixel is assigned to one of these clusters.

## Features

- **Preprocessed Grayscale Image:**
  - Convert the input image to grayscale for clustering.
- **Clustering with Different \(k\) Values:**
  - \(k=2\): Produces two distinct clusters.
  - \(k=3\): Produces three distinct clusters.
  - \(k=9\): Produces nine distinct clusters.

## Workflow

1. **Visualization:**
   - Reconstruct clustered images based on the assigned cluster labels.
   - Display the results for each \(k\) value.

2. **K-Means Clustering:**
   - Perform clustering for different \(k\) values (\(k=2\), \(k=3\), \(k=9\)).
   - Assign each pixel to the nearest cluster centroid.

3. -  **Preprocessing:**
   - Convert the input image to grayscale (for intensity-based clustering).
   - Flatten the image into a 2D array for clustering.

## Prerequisites

- Python 3.x
- OpenCV 4.x
- NumPy
- Matplotlib

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository/image-clustering.git
   ```
2. Navigate to the project directory:
   ```bash
   cd image-clustering
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch the script or notebook.

## Usage

1. Replace `path/to/image.jpg` with the path to your desired image file.
2. Run the script or notebook to generate clustered images for \(k=2\), \(k=3\), and \(k=9\).
3. View and analyze the results.

## Outputs

1. **Preprocessed Grayscale Image:**  
   The grayscale version of the input image.
2. **Clustered Images for \(k=2\), \(k=3\), and \(k=9\):**  
   Visualizations showing the segmented results for different numbers of clusters.
   ![Clustered](https://github.com/Deeksha1054/Image-Segmentation/blob/main/cluster.png)
    ![k=2](https://github.com/Deeksha1054/Image-Segmentation/blob/main/k%3D2.png)
    ![k=3](https://github.com/Deeksha1054/Image-Segmentation/blob/main/k%3D3.png)
    ![grayscale_k=9](https://github.com/Deeksha1054/Image-Segmentation/blob/main/gray%2Bk%3D9.png)


under guidance of:
Dr Agughasi Victor Ikechukwu (https://github.com/Victor-Ikechukwu)
