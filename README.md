# Building-GANs-model-using-tensorflow
This project demonstrates how to build and train a Generative Adversarial Network (GAN) using TensorFlow in Python 3.11.0. The GAN is trained on the classic MNIST dataset, which consists of handwritten digits, to generate new, realistic-looking digit images.

🧠 Generative Adversarial Networks (GANs) consist of two neural networks — a generator and a discriminator — that train together in a game-like setup. The generator creates fake data (e.g., images), while the discriminator tries to distinguish real data from the fake. The generator improves by trying to fool the discriminator, and the discriminator gets better at spotting fakes. This adversarial training continues until the generator produces data so realistic that the discriminator can’t tell the difference. GANs are widely used for image generation, style transfer, and data augmentation.

![gans architecture](https://github.com/user-attachments/assets/a645a33d-006a-4400-a11c-308b6ab8a3e1)

🛠 Technologies Used
Python 3.11.0

Note: TensorFlow is not supported on Python versions above 3.11 and below 3.8

TensorFlow (Deep Learning Library)

MNIST Dataset (from tensorflow.keras.datasets)

Matplotlib / NumPy for visualization and array manipulation

📌 Project Overview
Implementation of a basic GAN architecture

Training process includes:

Generator learns to create fake MNIST images

Discriminator learns to distinguish real from fake

After several epochs, the generator is able to produce images similar to real handwritten digits

Includes code comments and explanations to help beginners understand how GANs work

📷 Sample Outputs
The project includes image grids of generated digits at various training stages to visualize learning progress.

🔍 Learning Focus
This project is ideal for anyone who wants to:

Learn how GANs operate

Understand adversarial training dynamics

Explore deep learning model development using TensorFlow

📁 Dataset
MNIST dataset (loaded directly via tensorflow.keras.datasets.mnist)

🚀 Getting Started

Clone the repo

Install dependencies:
tensorflow,
matplotlib and
numpy

Run the jupyter notebook
