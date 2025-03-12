# EXP-6-A-
The **Mean Medium Max Filter (IPMV)** combines mean, median, and maximum filters to enhance image processing. It reduces noise while preserving important features like edges by calculating the mean, median, and maximum values within a local neighborhood. 
Mean Filter: This filter computes the average (mean) of the pixel values within a local neighborhood (a window) and replaces the central pixel with the calculated mean value. This operation helps in reducing high-frequency noise by averaging the pixel values, but it may blur edges.

Median Filter: In this filter, the central pixel in the neighborhood is replaced by the median of all the pixels in the window. Median filters are particularly effective for removing salt-and-pepper noise, preserving edges while smoothing out random noise.

Maximum Filter: This method replaces the central pixel with the maximum pixel value in the neighborhood. It is generally used to enhance the brightest pixels in an image, which may be useful for removing darker noise or enhancing features.
