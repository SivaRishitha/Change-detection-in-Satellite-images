
#  Change Detection in Satellite Imagery

This project demonstrates a simple yet effective algorithm to detect changes between two satellite images taken at different times. The goal is to identify areas of significant change, such as deforestation, urban expansion, or natural disasters.

## Features

- Image preprocessing: resize, align, denoise, normalize
- Change detection using:
  - Image subtraction
  - Otsu's thresholding
  - Adaptive thresholding
- Visualizations: histograms, boxplots, binary maps, and heatmaps

## Libraries Used

- OpenCV (for thresholding)
- Rasterio (for image processing)
- Matplotlib & Seaborn (for visualization)
