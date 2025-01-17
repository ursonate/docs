# Tutorial: Playing with Text to Image (AttnGAN)

Runway allows you to use and experiment with machine learning models without typing a single line of code. In this tutorial we will be using an model called [AttnGAN: Fine-Grained Text to Image Generation with Attentional Generative Adversarial Networks](https://github.com/taoxugit/AttnGAN/) by Tao Xu et al. to **generate images based on text.** This is the same model you can find in the interactive web experiment [Text2Image](https://t2i.cvalenzuelab.com/).


### Requirements

- Runway


### Step 1

The first step is to select the model **AttnGAN** from the Model Directory:

![GAN, AttnGAN with Runway, step 1](assets/images/tutorials/tutorial_t2i/01_model.png)

### Step 2

Next, add the model to a workspace from the top right side of the app.

![GAN, AttnGAN with Runway, step 2](assets/images/tutorials/tutorial_t2i/02_select.png)

### Step 3

If you haven't installed **AttnGAN**, the bottom right button will prompt you to install the model.  **You need to have Docker installed in order to continue.**

![GAN, AttnGAN with Runway, step 3](assets/images/tutorials/tutorial_t2i/attn02.jpg)


?> Some deep learning models might be large so please note that downloading the model might take a couple of minutes. In this case, AttnGAN might take **4 to 8 minutes** to download depending on your internet connection.

![GAN, AttnGAN with Runway, step 3](assets/images/tutorials/tutorial_t2i/attn03.jpg)

### Step 4

Once the model is installed, you will be able to use it.

On the I/O View select the **Local** option in the **Output** dropdown.

![GAN, AttnGAN with Runway, step 5](assets/images/tutorials/tutorial_t2i/attn05.jpg)


### Step 6

Next, click the **Run AttnGAN** button on the bottom right corner.

![GAN, AttnGAN with Runway, step 5](assets/images/tutorials/tutorial_t2i/attn06.jpg)


### Step 7

Once the model is running, you will be able to type anything in the **Text** input box and generate your own A.I based images based on your text!

![GAN, AttnGAN with Runway, step 5](assets/images/tutorials/tutorial_t2i/attn07.jpg)


### Summary

This tutorial shows how to use [AttnGAN](https://github.com/taoxugit/AttnGAN/), a Generative Adversarial Neural Network (GAN) that was trained to generate images from text.
