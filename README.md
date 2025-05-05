# DIP-PROJECT1
Salt and Pepper Noise Addition to Color Images
This project demonstrates how to add Salt-and-Pepper noise to color images using Python. You can adjust the noise level by modifying the salt and pepper probabilities.

Requirements
Python 3.x

OpenCV: pip install opencv-python

NumPy: pip install numpy

Matplotlib: pip install matplotlib

Code Explanation
Load Image: Uses cv2.imread() to load the image.

Add Noise: Adds Salt-and-Pepper noise by randomly setting some pixels to black (pepper) or white (salt).

Display Images: Displays both the original and noisy images using matplotlib.

How to Run
Place the image in the same directory or specify the path.

Run the Python script.

bash
Copy
Edit
python add_noise.py
The output will display the original and noisy images side by side.

Adjusting Noise Levels
Increase Noise: Set salt_prob = 0.5 and pepper_prob = 0.5 for 50% noise.

Decrease Noise: Set salt_prob = 0.05 and pepper_prob = 0.05 for less noise.

Example
python
Copy
Edit
salt_prob = 0.2  # 20% salt noise
pepper_prob = 0.2  # 20% pepper noise
License
Open-source project for educational purposes.

