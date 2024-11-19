# -Document-Scanning-with-Python

A Python-based tool to transform photos of documents into clean, scanned-like images using libraries like OpenCV, NumPy, and Skimage. This project automates image preprocessing, contour detection, and perspective correction, providing high-quality document scans from raw images.

Features

Image Preprocessing: Grayscale conversion, Gaussian blurring, and edge detection.

Contour Detection: Identifies document boundaries in images.

Perspective Correction: Warps the document to a flat, straightened view.

Visualization: Before-and-after image comparison for better insights.

Technologies Used

Python

OpenCV

NumPy

Skimage

Matplotlib

How It Works

Load Image: Import your document image into the script.

Preprocessing: Apply blurring and edge detection to highlight the document's outline.
Detect Contours: Identify and isolate the document boundary.

Transform Perspective: Use the contour points to straighten and warp the document.

Visualize Results: Display the original and scanned images side by side.
