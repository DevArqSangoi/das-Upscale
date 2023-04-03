# RealESRGAN Image Upscaling Script

This script is an easy-to-use implementation of the RealESRGAN model for upscaling images. RealESRGAN is a state-of-the-art deep learning model designed for enhancing the resolution and quality of images. The script allows users to select a source folder containing images, a destination folder for the upscaled images, and a pre-trained model file. The upscale factor (2x, 4x, or 8x) can be chosen according to the user's preference. The script supports various common image formats such as JPEG, PNG, BMP, TIFF, and WebP. In addition to the upscaled images, the script also saves the original images with a "original_" prefix in the destination folder.

For more information about the RealESRGAN model and its implementation, visit the original repository by the authors: [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)

## Dependencies

To run the script, you will need to have the following dependencies installed:

1. Python 3.x
2. OpenCV (cv2)
3. PyTorch (torch)
4. BasicSR (basicsr)
5. NumPy (numpy)
6. Tkinter (tkinter)
7. tqdm (tqdm)

## Usage

Upon execution, the script will prompt the user to select the input and output folders, as well as the path to the pre-trained RealESRGAN model. The user will then be asked to input the desired upscale factor (2x, 4x, or 8x). The script will upscale all the images in the input folder and save them alongside the original images in the output folder.

The upscaling process can significantly improve the quality and resolution of images, making it useful for various applications such as enhancing photographs, restoring old or low-quality images, and improving the visual quality of images for printing or display purposes.
