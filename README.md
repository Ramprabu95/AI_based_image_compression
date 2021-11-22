# AI_based_image_compression
**Code written according to the design of the below mentioned paper:**

M. Li, W. Zuo, S. Gu, D. Zhao and D. Zhang, "Learning Convolutional Networks for Content-Weighted Image Compression," 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2018, pp. 3214-3223, doi: 10.1109/CVPR.2018.00339.

**Introduction:**

This software takes a image as input. It compresses the image by passing it through a CNN based encoder. The software uses a content-weighted importance map for better reconstruction of complex textures and structures. This code is taken by the decoder and the reconstructed image is shown as the output. 

The software also gives the peak signal to noise ratio (PSNR) and structural similarity index (SSIM) between the input image and output image to know the quality of reconstruction.

**Requirements for installation and execution:**

All required python packages are imported by the software. The packages that are imported by the software include:

1. Pytorch
2. numpy
3. tensorflow
4. matplotlib

The software should run as a Jupyter notbook on Google Colab with Runtime as GPU and High RAM for quicker results.

**Dataset and Inputs Required:**

Training and testing was done on a subset of Image net dataset and validated. The images are to be downloaded and split into training and testing files manually. These files are to be stored in seperated folders in the google drive. The software attaches to google drive to access the dataset.

The software takes the path of test directory and train directory as inputs. There would be prompts like "Enter the train directory path:" and "Enter the test directory Path:" in the output regions of the cells. The path to the training and testing folders are to be entered in these prompts. No other input is required for the software.

**Output**
The output contains the original image, importance map and the reconstructed image. A sample output is shown below:

