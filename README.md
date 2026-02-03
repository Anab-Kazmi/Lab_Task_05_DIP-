# **Task 05: Spatial Filtering & Convolution**

**Roll Number:** 2023-SE-06

### **Prompt**

*"Write a complete Python program for LAB 5 – Spatial Filtering & Convolution using OpenCV, NumPy, SciPy, and Matplotlib, fully compatible with Google Colab. The program should satisfy all Digital Image Processing lab requirements as follows:

* Allow the user to upload a grayscale image and display the original image.
* Add Salt & Pepper noise and Gaussian noise separately to the image and display both noisy images.
* Apply the following spatial domain smoothing filters on both noisy images:

  * Mean Filter (3×3)
  * Median Filter (3×3)
  * Gaussian Filter (3×3)
* Apply a Laplacian filter for image sharpening and display the sharpened image.
* Implement a custom 3×3 convolution kernel manually using NumPy and apply it to the image.
* Display all results in a clear, well-organized comparison figure with proper titles and axes turned off.
* Compare the performance of each filter in terms of noise removal, edge preservation, and blurring.
* Clearly identify the best filter for Salt & Pepper noise and Gaussian noise, and justify the answer.
* Print a short analysis section summarizing the observations of each filter.
* Ensure the code is clean, well-commented, logically structured, and suitable for direct lab submission."*

---

## **Objective**

The objective of this task is to analyze the effectiveness of different **spatial domain filters** in removing noise and enhancing images. It focuses on **noise removal**, **edge preservation**, and **image sharpening** using both standard and custom convolution techniques.

---

## **Methodology / Approach**

1. Upload a **grayscale image** in Google Colab using `files.upload()` and display the original image.
2. Add **Salt & Pepper noise** and **Gaussian noise** separately to the image and display the noisy results.
3. Apply **spatial smoothing filters** on the noisy images:

   * **Mean Filter (3×3)**
   * **Median Filter (3×3)**
   * **Gaussian Filter (3×3)**
4. Apply a **Laplacian filter** to sharpen the original image.
5. Implement a **custom 3×3 convolution kernel** using NumPy and apply it to the image for edge detection.
6. Display all processed images in a well-organized figure for comparison.
7. Analyze the performance of each filter regarding noise reduction, edge preservation, and blurring.

---

## **Results / Observations**

* **Median Filter** is the most effective for **Salt & Pepper noise**, preserving edges while removing noise.
* **Gaussian Filter** works best for **Gaussian noise**, effectively smoothing the image.
* **Mean Filter** reduces noise but introduces noticeable blurring.
* **Laplacian Sharpening** enhances edges but amplifies noise in the image.
* **Custom 3×3 convolution** highlights edges and fine details effectively.
* Side-by-side comparison allows clear evaluation of each filter’s strengths and weaknesses.

---

## **Tools and Libraries Used**

* **Python 3.x**
* **OpenCV (cv2):** Image reading, filtering, and convolution
* **NumPy (np):** Noise addition, array manipulation, and custom convolution
* **SciPy (ndimage):** Custom convolution application
* **Matplotlib (plt):** Visualization of original, noisy, and filtered images
* **Google Colab:** Image upload and execution environment

---

