# DCGAN-Monet-Paintings
This projects utilized DCGAN, a deep learning concept utilizing general Generative Adversarial Networks, to create images in the style of one of the great french masters: Claude Monet

This project is in response to a Kaggle competition found here: https://www.kaggle.com/competitions/gan-getting-started/overview , whereby users are challenged to use GAN (Generative Adversarial Networks) to create a set of 7000-10000 images in the style of Monet to demonstrate their knowledge of this Deep Learning tool.

A General Adversarial Network is a framework used in deep learning, comprised of two neural networks: A Generator and a Discriminator. The Genererator created fake data (images in this case), while the Discriminator judges whether the data is real or fake. These two neural networks work in tandem with each other, each gaining feedback from each other to increase the efficacy of the data output. This process is iterated over continually until the data generated is realistic enought that the discriminator cant distinguish between real and fake data.

The data in this competition is two-fold: 1. A set of Monet paintings and 2. A set of Photos that users are challenged to emmulate in the style Monet.

It should be noted though, that the Kaggle Competition also specifies that users may decided to create their own images from scratch, rather than use the photos provided to be transformed in the likeness of Monet-Style paintings.

As per the competition description:

"Note: Monet-style art can be created from scratch using other GAN architectures like DCGAN. The submitted image files do not necessarily have to be transformed photos."

This project will take the route of generating new images in the style of the Monet paintings, use DCGAN, rather than transforming the existing photos to Monet-style images. DCGAN is an extension of GAN methodology that utilizes convulutional layers in model architecture, and is more suited for image data such as what is provided in this project.
