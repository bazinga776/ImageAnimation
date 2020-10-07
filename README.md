# ImageAnimation
Rotate, Flip the input image

Used `numPy` and `opencv` modules of python for performing operations on a input image(PNG File) and return an output video File

```python
Usage: animate.py <input_image.png> <output_file.mp4> optional: <transform_type>
```
* transform_type = 0: rotation
* transform_type = 1: vertical flip
* transform_type = 2: horizontal flip
* transform_type = 3: vertical+horizontal flip
Valid output formats include .m4a .mp4 .mov .avi

Input image required Format: NxN where 2^N exists

If the input image dimensions are not in required format, the image is cropped to the nearest power of 2.



