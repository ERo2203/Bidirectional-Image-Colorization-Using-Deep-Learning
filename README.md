# Bidirectional-Image-Colorization-Using-Deep-Learning

Image colorization, the process of adding color to grayscale images, has evolved significantly with deep learning. This article discusses a bidirectional approach to image colorization, using neural networks to colorize grayscale images and grayscale color images.

The method employs Convolutional Neural Networks (CNNs) to learn the intricate mappings between grayscale and color images. By training on a large dataset of paired grayscale and color images, the model can accurately predict colors for grayscale images and convert color images to grayscale.

The implementation involves two primary files: `GreytoColor.py` and `ColortoGrey.ipynb`. The `GreytoColor.py` script includes the model definition, data loading, preprocessing, and the main functions for colorizing and grayscaling images. The model architecture consists of convolutional layers for feature extraction and upsampling layers for image reconstruction. The script handles data normalization and conversion to the LAB color space, essential for the colorization process.

The Jupyter notebook, `ColortoGrey.ipynb`, complements the script by providing detailed steps for data visualization, model architecture, training, and result visualization. It allows for interactive exploration and fine-tuning of the model, making it easier to understand the data and the model's performance.

This bidirectional approach demonstrates the effectiveness of deep learning in automating and enhancing the image colorization process. Future improvements can focus on refining the model architecture and experimenting with different datasets to achieve better results and generalization. This technique has potential applications in image restoration, content creation, and digital art.

# Dataset link: 
https://shorturl.at/FU9lD
