Applied Deep Learning: Implementing CNN Architectures
This repository contains implementations and pre-trained models for various Convolutional Neural Network (CNN) architectures, ranging from foundational to advanced designs. These resources are part of the "Applied Deep Learning" series.


## Large Files
The pre-trained model (AlexNet) are too large for GitHub. You can download it from
[Google Drive](https://drive.google.com/file/d/15XuAMMx2Iw5GPsS7x9Qz1wtkzsa6CQ87/view?usp=drive_link)


## Images
Contains all images used in the project, These images are referenced in notebooks and documentation
[Dropbox](https://www.dropbox.com/scl/fo/0dsnw3wbztbya3yvu6l5t/ADquxSfF_NSxUH6Wo0Td6UI?rlkey=u6hfak0bwx4tj407v3ooghnln&st=fwkpamd2&dl=0)


📂 Files and Descriptions
1. LeNet.h5
Description: Pre-trained model of the LeNet architecture.
Details:
LeNet was introduced by Yann LeCun and is a pioneering CNN model, primarily used for handwritten digit recognition.
2. AlexNet.h5
Description: Pre-trained model of AlexNet.
Details:
AlexNet was the first CNN architecture to achieve groundbreaking results in the ImageNet competition, known for its deeper and more complex layers.
3. multiple_vgg_blocks.h5
Description: Model implementing multiple VGG blocks.
Details:
Based on the VGG architecture, this model emphasizes simplicity and uses deep, stacked convolutional layers.
4. residual_module.h5
Description: Pre-trained model featuring Residual Connections.
Details:
Inspired by ResNet, this architecture introduces skip connections to address vanishing gradient issues in deeper networks.
5. inception_module_advanced.h5
Description: Model using an advanced Inception Module.
Details:
Inspired by Google's Inception architecture, this model is designed for multi-scale feature extraction and improved computational efficiency.

⚙️ Prerequisites
Before using these files, ensure the following:

Python: Version 3.x
Libraries:
TensorFlow >= 2.x
Keras >= 2.x
NumPy, Matplotlib
Jupyter Notebook and Colab: For running .ipynb files


💡 Applications
These models and notebooks can be used for:

Learning: Understand the design and working of CNN architectures.
Transfer Learning: Fine-tune models on your custom datasets.
Research: Benchmark CNN architectures for specific tasks.
📜 License
This repository is licensed under the MIT License.

🙏 Acknowledgments
This work is inspired by seminal papers and architectures in the field of deep learning:

LeNet: Yann LeCun et al.
AlexNet: Alex Krizhevsky et al.
ResNet: Kaiming He et al.
VGG: Karen Simonyan et al.
Inception: Christian Szegedy et al.
