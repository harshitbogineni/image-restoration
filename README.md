# Deep Learning for Image Restoration

This repository contains a TensorFlow and Keras-based implementation for various image restoration tasks, including denoising, inpainting, and super-resolution. The project demonstrates the model's effectiveness on a variety of images, including medical scans (MRI), histology slides, and general photographs.

## 🖼️ Project Overview
The core of this project is a deep learning model designed to reconstruct high-quality images from corrupted or low-quality inputs. The `image_restoration.ipynb` notebook provides a complete workflow, from setting up the environment to processing images and visualizing the results.

The primary tasks handled by this project are:

- **Image Denoising**: Removing noise from images at various levels (low, medium, high).
- **Image Inpainting**: Reconstructing missing or damaged parts of an image.
- **Super-Resolution**: Increasing the resolution and detail of a low-resolution image.


##  Getting Started

To run this project on your own machine, follow these steps.

### Prerequisites
Make sure you have Python 3.x installed. You will also need to install the required libraries. It's recommended to create a `requirements.txt` file with the following content:

```
tensorflow
numpy
matplotlib
scikit-image
opencv-python-headless
```

Then, you can install them using `pip`:

```bash
pip install -r requirements.txt
```

### Usage

1. **Clone the repository**:

```bash
!git clone https://github.com/harshitbogineni/image-restoration
cd YOUR_REPOSITORY
```

2. **Open the Jupyter Notebook**:
Launch Jupyter Notebook and open `image_restoration.ipynb`.

```bash
jupyter notebook image_restoration.ipynb
```

3. **Run the cells**:
Execute the cells in the notebook to download the model, process the sample images, and see the restored outputs. The results will be saved in the `recovered_images/` directory.
