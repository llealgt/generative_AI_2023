# Generative AI 2023

A repository about generative AI created in 2023 to host experiments, paper implementations, tutorials and course examples(mainly for universidad Galileo) with the goal of refreshing my memory of some things I did in the past, learning new  things and sharing(if possible). 


## Pre-2023
Some things I did in the past(from around 2016-2018):

* Autoregressive:
	* ["The simpsons"  tv script generator](https://github.com/llealgt/The_simpsons_scripts_writer/blob/master/dlnd_tv_script_generation.ipynb): recurrent neural networks used to generate tv scripts(text) for the "simpsons"
	* [Edgar Phillips LovePoe(generate stories combining Lovecraft and Poe)](https://github.com/llealgt/edgar_philip_love_poe): recurrent neural networks(LSTM) used to generate stories that mix H.P Lovecraft and Edgar Poe styles.
* GANs:
	* [DCGAN for MNIST digits and face generation](https://github.com/llealgt/dcgan_face_generation/blob/master/dlnd_face_generation.ipynb): deep convolutional GAN applied to the MNIST(to generate digits) dataset and the celeba dataset(to generate faces).
	* [DCGAN for SVHN(street view house numbers)](https://github.com/llealgt/DCGAN_SVHN): deep convolutional GAN applied to the SVHN(to generate house numbers) dataset .
	* [GAN for video/animation generation of "ARRIVAL" movie circles](https://github.com/llealgt/MNIST_GAN/blob/master/Video%20Generation%20GAN.ipynb): GAN used to generate the "signs/languaeg" from the [movie "ARRIVAL"](https://youtu.be/tFMo3UJ4B4g?t=95). Some results:

	![](https://github.com/llealgt/MNIST_GAN/blob/master/animation.gif)
	![](https://github.com/llealgt/MNIST_GAN/blob/master/animation1503556347.gif)

* Autoencoders
	* [Simple auto-encoder for MNIST](https://github.com/llealgt/Autoencoders/blob/master/Simple_Autoencoder.ipynb): a vanilla autoencoder using the MNIST dataset
	* [Convolutional auto-encoder for MNIST](https://github.com/llealgt/Autoencoders/blob/master/Convolutional_Autoencoder.ipynb) : a convolutional autoencoder applied to the MNIST dataset
	* [Convolutiona auto-encoder for genoising MNIST](https://github.com/llealgt/Autoencoders/blob/master/Convolutional%20Autoencoder%20For%20Denoising.ipynb): a denoising autoencoder applied to the MNIST dataset
	* [Variational auto-encoder](https://github.com/llealgt/Autoencoders/blob/master/Varational%20Autoencoder.ipynb):  a variational autoencoder applied to the mnist dataset


## Post-2023


* Autoregressive:
	* [PixelCNN from Pixel RNNs paper](https://github.com/llealgt/generative_AI_2023/blob/main/PixelCNN.ipynb): PixelCNN applied to MNIST from the paper "pixel recurrent neural networks"
	* [LLM parameter-efficient fine-tuning](https://github.com/llealgt/generative_AI_2023/blob/main/Lab_2_fine_tune_generative_ai_model.ipynb): LLM fine-tuned using parameter-effficient fine-tuning(LoRA)
* [Basic GAN](https://github.com/llealgt/generative_AI_2023/blob/main/basic_GAN.ipynb): just a good old original GAN.
* [Conditional GAN](https://github.com/llealgt/generative_AI_2023/blob/main/ConditionalGAN.ipynb): just a super simple conditional gan using MNIST(given a digit label generate an image of that digit)
* [Wasserstein GAN with gradient penalty for face generation](https://github.com/llealgt/generative_AI_2023/blob/main/AdvancedGAN(WGAN-GP).ipynb) : a WGAN-GP for face generation

	![](https://github.com/llealgt/generative_AI_2023/blob/main/wgan_output.png?raw=true) 
	![](https://github.com/llealgt/generative_AI_2023/blob/main/wgan_output2.png?raw=true)

* [GAN with adaptive discriminator augmentation and kernel inception distance](https://github.com/llealgt/generative_AI_2023/blob/main/GAN_ADA.ipynb): GAN with adaptive discriminator augmentation to prevent discriminator from overfiting and kernel inception distance to measure quality of generated images.

* [Multimodal generation(text to image) using VQGAN+CLIP](https://github.com/llealgt/generative_AI_2023/blob/main/MultiModalGeneration(VQGAN%2BCLIP).ipynb): vector quantized gan + contrastive language-image pretraining for generating images from text.

![](https://github.com/llealgt/generative_AI_2023/blob/main/output.gif)
![](https://github.com/llealgt/generative_AI_2023/blob/main/output2.gif)
![](https://github.com/llealgt/generative_AI_2023/blob/main/output3.gif)
![](https://github.com/llealgt/generative_AI_2023/blob/main/output4.gif)
![](https://github.com/llealgt/generative_AI_2023/blob/main/output5.gif)
* Diffusion Models
	* [Simple diffusion from paper "Denoising Diffusion Probabilistic Models" with MNIST](https://github.com/llealgt/generative_AI_2023/blob/main/SimpleDiffusion.ipynb)