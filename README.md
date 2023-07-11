# CGAN-Network

This is a conditional generative adversarial network (CGAN) project that focuses on generating realistic images of the numbers 0 to 9.

## Notebook Description

The generator uses two main components: a generator and a discriminator. The generator takes a random input and generates an image that resembles a number. The discriminator, on the other hand, attempts to distinguish between the generated images and real number images.

During training, the generator and the discriminator improve each other in an iterative process. The generator seeks to generate increasingly realistic images to fool the discriminator, while the discriminator trains itself to become better and better at distinguishing fake images from real ones.
