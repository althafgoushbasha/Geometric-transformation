README - Geometric Transformations Notebook

This notebook demonstrates how to perform and visualize four different geometric transformations 
(Euclidean, Similarity, Affine, and Projective) using Python libraries such as scikit-image, NumPy, 
OpenCV, and Matplotlib.

---
1. Euclidean Transformation
   - Imports an image from skimage's sample dataset.
   - Applies rotation and translation using EuclideanTransform from skimage.
   - Visualizes the transformed image with matplotlib.

2. Similarity Transformation
   - Defines scaling, rotation, and translation parameters.
   - Uses SimilarityTransform to apply the transformation.
   - Displays the result, showing how shape is preserved but size/orientation changes.

3. Affine Transformation
   - Creates a custom affine transformation matrix.
   - Uses AffineTransform to warp the image.
   - Shows effects like shearing, scaling, rotation, and translation.

4. Projective Transformation
   - Defines 4 points in the source image and maps them to 4 points in the output.
   - Uses ProjectiveTransform to compute the mapping.
   - Displays perspective transformation, where straight lines remain straight but parallelism is not preserved.

---
Requirements:
- Python 3.x
- numpy
- matplotlib
- scikit-image
- opencv-python

To run:
1. Install the requirements with pip.
2. Open Transformations.ipynb in Jupyter Notebook.
3. Run the cells sequentially to see each transformation applied and visualized.

