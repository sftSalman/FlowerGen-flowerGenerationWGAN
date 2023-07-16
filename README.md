# Oxford Flower Dataset - WGAN Image Generation - 


![Screenshot 2023-06-22 232224](https://github.com/sftSalman/FlowerGen-flowerGenerationWGAN/assets/33355278/1dfc7607-d969-405c-82ab-031709795843)

This project focuses on using the Oxford Flower dataset to train a Wasserstein Generative Adversarial Network (WGAN) for generating realistic flower images. The WGAN model learns the underlying patterns and distribution of flower images and generates new images that resemble the training data.

## Dataset

The Oxford Flower dataset consists of images of flowers categorized into 102 different classes. The Oxford Flower dataset, A large collection of flower images with 17 categories, containing images of various flower species. It provides a rich collection of flower images suitable for training the WGAN model. The dataset can be downloaded from [kaggle](https://www.kaggle.com/competitions/oxford-102-flower-pytorch/data).


# Key Features:

- WGAN architecture for flower generation
- Training on The Oxford Flower dataset
- Implementation based on PyTorch
- Transformations applied to the dataset include resizing, center cropping, and normalization
- Generator and critic models are included
- TensorBoard integration for visualizing real and generated images during training
- Saved model checkpoints for the generator, critic loss, and generator loss for further use
- By using this code, you can generate realistic flower images with diverse colors, shapes, and patterns. The trained model can be used for various applications, such as data augmentation, 
 artwork generation, or as a starting point for further fine-tuning.

Feel free to explore the code, experiment with different hyperparameters, and contribute to the project to enhance the flower generation capabilities using WGAN.


# Requirements:

- PyTorch
- torchvision
- tqdm
- tensorboard

# Instructions:

Download The Oxford Flower dataset.
Set the dataset path in the code.
Adjust the hyperparameters, such as learning rate, batch size, and number of epochs, according to your needs.
Run the code and visualize the training progress using TensorBoard.
Start generating beautiful flower images with WGAN today!


# Hypermeter 
`LEARNING_RATE = 5e-5
BATCH_SIZE = 64
IMAGE_SIZE = 64
CHANNELS_IMG = 3
Z_DIM = 128
NUM_EPOCHS = 20
FEATURES_CRITIC = 64
FEATURES_GEN = 64
CRITIC_ITERATIONS = 5
WEIGHT_CLIP = 0.01
`

