# face-generator
Face Generator Project is a part of Udacity Deep Learning Nanodegree.

# Project overview
Developed generative adversarial networks to generate new images of faces that look as realistic as possible!.
The model is trained on the CelebFaces Attributes Dataset (CelebA):

![Alt text](assets/processed_face_data.png?raw=true "Dataset")

It generates new human faces as follows:

![Alt text](assets/output.png?raw=true "output")

Udacity original repo: https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-face-generation

# Technology Used
- Python Frameworks (NumPy, Pytorch, OpenCV, Matplotlib, etc.)
- Deep Convolutional Generative Adversarial Networks

# References 
- [Wasserstein GAN](https://arxiv.org/abs/1701.07875) as it's GAN with an objective and thus has a convergence criterion.
- For, Generative Models in general, check https://blog.openai.com/generative-models/
- [DiscoGAN](https://github.com/carpedm20/DiscoGAN-pytorch), [Discover Cross-Domain Relations with Generative Adversarial Networks](https://github.com/carpedm20/DiscoGAN-pytorch)
- For more on GAN stability, check http://www.araya.org/archives/1183.
- [MNIST GAN with Keras](https://medium.com/towards-data-science/gan-by-example-using-keras-on-tensorflow-backend-1a6d515a60d0) which shows that how much concise can one be when modelling neural networks.
- How to Train a GAN: https://github.com/soumith/ganhacks
- Making pixel art with GANs, check https://medium.com/@ageitgey/abusing-generative-adversarial-networks-to-make-8-bit-pixel-art-e45d9b96cee7
- Also go through current standard technique for making high resolution images: [Progressive Growing of GANs for Improved Quality, Stability, and Variation](https://arxiv.org/abs/1710.10196)
- [BigGANs: Large-Scale GAN ](https://twitter.com/ajmooch/status/1046556635446079488) is one of very influential papers of last year in generative modelling. TLDR: Twitter thread by the author.
- Another interesting read is the [Style-Based GAN](https://arxiv.org/abs/1812.04948). You can also see its results on the website thispersondoesnotexist.com.
- A blog going through variety of GANs and comparing them: https://medium.com/datadriveninvestor/a-leap-into-the-future-generative-adversarial-networks-96a780ed8ee6