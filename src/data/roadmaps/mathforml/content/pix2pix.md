# Pix2Pix

- pix2pix is shorthand for an implementation of a generic image-to-image translation using conditional adversarial networks, originally introduced by Phillip Isola et al. Given a training set which contains pairs of related images (“A” and “B”), a pix2pix model learns how to convert an image of type “A” into an image of type “B”, or vice-versa. For example, suppose we have pairs of images, where A is a black & white image and B is an RGB-color version of A.

## The architecture of your network will contain:

- A generator with a U-Net-based architecture.
- A discriminator represented by a convolutional PatchGAN classifier (proposed in the pix2pix paper).

## YOUTUBE:
[Pix2Pix implementation from scratch](https://www.youtube.com/watch?v=SuddDSqGRzg)

[Pix2Pix Paper Walkthrough](https://www.youtube.com/watch?v=9SGs4Nm0VR4)

[250 - Image to image translation using Pix2Pix GAN](https://youtu.be/UcHe0xiuvpg)

## coursera:
[Apply Generative Adversarial Networks (GANs)](https://www.coursera.org/learn/apply-generative-adversarial-networks-gans?=)

## Blog:
[neptune.ai](https://neptune.ai/blog/pix2pix-key-model-architecture-decisions)
