#Tasks
✅ Task 1: Reduce Intensity Levels
Reduces the number of intensity levels in a grayscale image. The number of levels is varied as powers of 2 from 2 to 128 (i.e., 2, 4, 8, ..., 128). The outputs are saved as:

bash
Copy
Edit
outputs/intensity_{levels}.png
✅ Task 2: Spatial Averaging
Applies a spatial average (blurring) filter using kernels of size 3×3, 10×10, and 20×20. Results are stored as:

bash
Copy
Edit
outputs/blur_{kernel_size}x{kernel_size}.png
✅ Task 3: Image Rotation
Rotates the input image by 45° and 90°. Bounding boxes are adjusted to avoid cropping. Output filenames:

bash
Copy
Edit
outputs/rotated_45.png
outputs/rotated_90.png
✅ Task 4: Blockwise Averaging
Performs blockwise averaging over non-overlapping blocks (3×3, 5×5, 7×7) and replaces all pixels in a block with the average value. This simulates spatial resolution reduction. Saved files:

css
Copy
Edit
outputs/blockwise_avg_{b}x{b}.png
How to Run
Ensure flower.png is in the root directory. Then run:

bash
Copy
Edit
python main.py
All output images will be saved in the outputs/ directory.
