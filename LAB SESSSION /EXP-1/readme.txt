

from google.colab import files
uploaded = files.upload()

import cv2
from google.colab.patches import cv2_imshow # Import Colab-compatible imshow

# Use the uploaded image filename instead of a local path
img = cv2.imread('Screenshot 2026-05-06 085125.png')

# It's good practice to check if the image loaded successfully
if img is None:
    print("Error: Could not load image. Please ensure the correct filename is used.")
else:
    gray_img = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
    # Use cv2_imshow for displaying images in Colab
    cv2_imshow(gray_img)
    cv2.imwrite('gray_image.jpg', gray_img)
    # cv2.waitKey(0) and cv2.destroyAllWindows() are not needed with cv2_imshow
    print("Grayscale image saved as 'gray_image.jpg'")
