# Project README

Please note that only 2 of the learned models are available here, for many more learnt models please contact~(each of GANs proposed has been trained for 9000 or more epochs).
# Devices Utilized for Training

- **MSI GF63 Thin 9SCSR Laptop**
  - 9th Gen. Intel® Core™ i7-9750H Processor
  - NVIDIA® GeForce® GTX 1650 Ti With Max-Q Design, 4GB GDDR6

- **Local Personal Computer (Home)**
  - Intel® Core™ i5-9400F Processor
  - NVIDIA® GeForce® GTX 1050 Ti

- **Google Colaboratory**
  - NVIDIA Tesla K80 GPU with 12GB of VRAM (Video Random-Access Memory)
  - Stopped after 500 epochs (limit)

## Provide the Code


## Larger GAN Versions

This repository contains implementations of Generative Adversarial Networks (GANs) for generating larger images. The models are available in two versions:

- **Larger GAN Version 1**: Please refer to the notebook [wgan_128_v1.ipynb](./wgan_128_v1.ipynb) for the implementation details and usage instructions.
- **Larger GAN Version 2**: Please refer to the notebook [wgan_128_v2.ipynb](./wgan_128_v2.ipynb) for the implementation details and usage instructions.

## Evaluation Metrics

To evaluate the performance of the GAN models, we use the Frechet Inception Distance (FID) scores. The evaluation results can be found in the `evaluations` folder.

For detailed FID scores and comparisons, please refer to the files within the [evaluations](./evaluations) directory.
