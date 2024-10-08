# GAN Project

This project focuses on building a Generative Adversarial Network (GAN) to generate color images with a resolution of 100x100 pixels.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Generative Adversarial Networks (GANs) are a class of machine learning frameworks designed to generate new data samples. In this project, a GAN is trained to generate images with dimensions 100x100 and 3 color channels. The network is composed of a generator that creates images and a discriminator that distinguishes between real and generated images.

## Installation

To install the required dependencies, run the following commands in your terminal:

```bash
git clone https://github.com/your-username/gan-project.git
cd gan-project
pip install -r requirements.txt
```
Make sure you have Python and the necessary libraries (e.g., TensorFlow or PyTorch) installed.

## Usage
After installing the dependencies, you can train the GAN model using the following command:
```bash
python train.py
```
Generated images will be saved in the outputs/ directory. To adjust hyperparameters such as batch size, number of epochs, or learning rate, modify the config.py file.

## Results

----
##Contributing
Contributions are welcome! Feel free to open issues or submit pull requests for bug fixes, improvements, or new features.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

### Adding Images:
- Replace `/content/flowers-five-classes1/train` with the actual paths to your images in the repository.
