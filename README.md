# ImageProcessingAssignment

This repository implements three image processing algorithms: RANSAC for outlier removal and transformation model fitting, Harris corner detector, and Shi-Tomasi corner detector. The code is written in Jupyter Notebooks, and outputs are saved as images.

## Algorithms
1. **RANSAC**: Removes outliers and fits a transformation model (`ransac.ipynb`, outputs: `ransac1.png`, `ransac2.png`).
2. **Harris Corner Detector**: Detects corners in grayscale images (`Harris.ipynb`, output: `harris_corners.png`).
3. **Shi-Tomasi Corner Detector**: Identifies corner points (`shi_tomasi.ipynb`, output: `shi_tomasi_corners.jpg`).

## Repository Structure
- `Harris.ipynb`, `ransac.ipynb`, `shi_tomasi.ipynb`: Code files.
- `harris_corners.png`, `ransac1.png`, `ransac2.png`, `shi_tomasi_corners.jpg`: Output images.
- `README.md`: This file.

## How to Run
1. Clone: `git clone https://github.com/Anshul3977/ImageProcessingAssignment.git`
2. Install: `pip install opencv-python numpy matplotlib`
3. Run the notebooks in Jupyter.
