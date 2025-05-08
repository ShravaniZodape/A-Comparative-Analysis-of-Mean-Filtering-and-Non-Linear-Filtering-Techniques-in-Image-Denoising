# A-Comparative-Analysis-of-Mean-Filtering-and-Non-Linear-Filtering-Techniques-in-Image-Denoising

Comparative analysis of image filtering techniques using PSNR and SSIM on UC Berkeley EECS dataset. Implemented in Google Colab with visual results and performance metrics.

## Abstract

This study investigates the effectiveness of various linear and non-linear filtering techniques for image denoising. Noise in digital images, often caused by acquisition or transmission errors, can severely impact visual quality and the accuracy of computer vision tasks. The goal is to restore image clarity while preserving important structural details.

## Filters Compared

- **Mean Filter** (Linear)
- **Median Filter**
- **Adaptive Median Filter**
- **Bilateral Filter**
- **Minimum Filter**
- **Maximum Filter**

These methods are tested against:
- Gaussian Noise
- Salt-and-Pepper Noise
- Speckle Noise

## Evaluation Metrics

- **PSNR** (Peak Signal-to-Noise Ratio)
- **SSIM** (Structural Similarity Index)
- **Execution Time** (Computational Efficiency)

## Dataset

- Sourced from the **EECS Department, University of California, Berkeley**

## Implementation

The entire analysis, including visual comparisons and performance graphs, is implemented in a Google Colab notebook.

📥 [Click here to view/download the Colab Notebook](https://colab.research.google.com/drive/1DOCZgpjFAxhrFOoxhKDxJT6M8I25anj-?usp=drive_link) 

## Key Findings

- **Mean Filtering** is effective for Gaussian noise but leads to edge blurring.
- **Median and Adaptive Median Filters** perform better on salt-and-pepper noise with preserved edge details.
- **Bilateral Filtering** balances noise suppression and edge retention but has higher computational cost.
- **Minimum and Maximum Filters** are effective but may distort image morphology.

## 🎯 Conclusion

Non-linear filters outperform Mean Filtering in preserving image structure and suppressing noise, especially in high-precision applications like medical imaging and surveillance. However, the trade-off lies in execution time and complexity, highlighting the importance of choosing filters based on application-specific needs.
