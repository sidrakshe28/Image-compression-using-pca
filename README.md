# Image-compression-using-pca
Using PCA for image compression

An image can be treated as a matrix - a grid of pixels, with values being the pixel intensities.

The basic steps are:

Apply PCA on the image matrix to reduce the dimensionality to a smaller number of principal components (PCs).

This is lossy compression, as we are discarding some of the information.

To assess how much visual information we retained, we'll reconstruct the image from the limited number of PC.

We'll see how good the reconstructed images are for different number of selecte components.
