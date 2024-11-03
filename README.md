
# 🎨 MNIST GAN Image Generator

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 📖 Project Overview

This project implements a **Generative Adversarial Network (GAN)** to generate realistic handwritten digits similar to those in the **MNIST dataset**. By training a generator to create images and a discriminator to classify them, we can produce high-quality digit images through adversarial training. This project is part of my **fourth task at my ML internship at EziTech**.

## 🚀 Features

- **Image Generation**: Generate new, high-quality handwritten digits.
- **Training Visualization**: Monitor training progress with generated images at each epoch.
- **Model Checkpointing**: Save the model periodically to prevent data loss and track improvements.
- **Customizable Training**: Easily adjust training parameters and dataset size.

## 📦 Getting Started

### Prerequisites

To run this project, you'll need:

- Python 3.x
- TensorFlow 2.x
- Keras (if not included with TensorFlow)

### Installation Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/MNIST_GAN_ImageGenerator.git
   cd MNIST_GAN_ImageGenerator
   ```

2. **Install Dependencies**:
   Create a virtual environment (optional but recommended) and install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## 🏋️ Training the Model

To train the GAN model, simply execute:

```bash
python train.py
```

The training process will generate images at specified epochs, showcasing the model's progress in generating realistic digits.

## 🖼️ Usage

After training, you can generate new images using the trained model:

```bash
python generate_images.py
```

The generated images will be saved in the `generated_images` directory for easy access.

## 📊 Results

The following images demonstrate the results of the GAN training process. As training progresses, you can observe the enhancement in image quality.

![Example Output](path/to/example_image.png) 

## 🤝 Contributing

We welcome contributions! If you have ideas for improvements or features, please fork the repository and create a pull request.

## 📜 License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify it!

## 🎉 Acknowledgements

- **MNIST Dataset**: For providing the handwritten digits dataset.
- **TensorFlow & Keras**: For the deep learning framework used in this project.
