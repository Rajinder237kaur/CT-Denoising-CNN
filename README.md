#CT Image Denoising Using Convolutional Neural Networks (CNNs)

This project explores the use of deep learning techniques for CT image denoising using Convolutional Neural Networks (CNNs) implemented in PyTorch. The primary objective is to improve noisy CT image quality while preserving important anatomical structures and image details.

##Project Motivation

Low-dose CT imaging is commonly used to reduce radiation exposure to patients; however, lowering the radiation dose introduces increased image noise and degradation in image quality. Image denoising techniques based on deep learning have shown promising results in reconstructing cleaner images while preserving diagnostically important features.

This project serves as an introductory exploration into:

Medical image processing
Deep learning for medical imaging
CT image denoising
CNN-based image reconstruction
Evaluation using image quality metrics
Methods

The project pipeline includes:

Loading and preprocessing CT DICOM images
Image normalization and windowing
Addition of synthetic noise
CNN-based denoising using PyTorch
Evaluation using PSNR and SSIM metrics
CNN Architecture

The implemented CNN architecture consists of:

Convolutional layers for feature extraction
ReLU activation for non-linearity
Reconstruction layer for denoised image generation

The model was trained using:

Mean Squared Error (MSE) Loss
Adam Optimizer
PyTorch deep learning framework
Results

The CNN demonstrated improvement in image quality after denoising.

Quantitative Metrics
Metric	Noisy Image	Denoised Image
PSNR	22.69	29.32
SSIM	0.256	0.644

These results indicate improved structural similarity and reduced noise in the denoised CT images.

Technologies Used
Python
PyTorch
NumPy
Matplotlib
pydicom
scikit-image
Jupyter Notebook
Visual Studio Code
