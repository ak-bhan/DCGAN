# DCGAN
# Anime Character Face Generation using DCGAN

## Dataset Description
The dataset used in this project is the [Anime Faces dataset](https://www.kaggle.com/soumikrakshit/anime-faces), which contains 21,551 high-quality images of anime faces. These images serve as the training data for both the discriminator and generator networks.

## Network Architecture
The network architecture closely follows the Deep Convolutional Generative Adversarial Networks (DCGAN) described in the research paper titled ["Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks"](https://arxiv.org/pdf/1511.06434.pdf) by Radford et al. The implementation follows the structure outlined in the paper to generate anime character faces.

### Technical Highlights
1. **Generator Network:** The generator network employs convolutional layers, generating synthetic anime character faces that closely resemble those in the dataset.

2. **Discriminator Network:** The discriminator network distinguishes between real and generated images using convolutional layers, continuously improving its ability to discern real from fake.

3. **Training Procedure:** The training process involves an adversarial interplay between the generator and discriminator networks. The generator strives to produce more convincing anime character faces, while the discriminator aims to improve its discrimination ability. Training continues until satisfactory image generation is achieved.

4. **Hyperparameters:** The repository includes hyperparameters such as learning rate, batch size, and the number of epochs used for training. These parameters can be adjusted for optimization.

5. **Results:** The generated anime character faces at various training epochs are provided in the 'DCGAN.ipynb', enabling users to observe the evolution of image quality during training.
