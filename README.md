# EXP3 Image-Enhancement-Smoothning-And-Sharpening

exp 3a

IMAGE SMOOTHING

Image smoothing refers to the process of reducing the noise or fine details in an image. It involves averaging pixel values within a neighborhood to blur or soften the image. The primary purpose of smoothing is to reduce high-frequency noise and smoothen abrupt changes in pixel intensity, making the image appear more uniform and less sharp. This is particularly useful when trying to remove unwanted noise or when preprocessing images for further analysis, such as object detection or segmentation.
There are several common smoothing techniques:
Gaussian Blur: Uses a Gaussian kernel, which weights pixel values based on their distance from the center. Pixels close to the center have higher weights, leading to a smoother effect.
Mean Filter (Average Filter): Averages the pixel values in a neighborhood and replaces the central pixel with this average.
Median Filter: Replaces the center pixel of a neighborhood with the median value of that neighborhood, making it especially effective for removing "salt and pepper" noise.

exp 3b

IMAGE SHARPENING

Image sharpening is a technique used to enhance the edges and fine details of an image. It highlights areas of rapid intensity change, making objects and textures more distinct. Sharpening is typically used to make an image appear clearer and more defined, especially in applications like object recognition, medical imaging, and photography.
Sharpening works by amplifying the high-frequency components (edges) while suppressing the low-frequency components (smooth areas). This is achieved by enhancing the differences between neighboring pixel values, making transitions more noticeable.
Some common sharpening methods include:
Laplacian Operator: The Laplacian filter detects edges by calculating the second derivative of the image, highlighting regions with rapid intensity changes.
Unsharp Masking: Involves subtracting a blurred version of the image from the original image to highlight edges. The result is an image that appears sharper.
High-pass Filtering: A high-pass filter removes low-frequency components (smooth areas), leaving behind the high-frequency components (edges), which enhances sharpness.
