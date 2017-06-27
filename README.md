# intro_gans

* In this,we are gonna building a generative adversarial network (GAN) trained on [MNIST](http://yann.lecun.com/exdb/mnist/) dataset.


* In **GANs** is that you have two networks, a **generator G**  and a **discriminator D** , competing against each other. The generator makes fake data to pass to the discriminator. The discriminator also sees real data and predicts if the data it's received is real or fake.
* The **generator** is trained to fool the **discriminator**, it wants to output data that looks as close as possible to real data. And the discriminator is trained to figure out which data is real and which is fake. What ends up happening is that the generator learns to make data that is **indistiguishable** from real data to the discriminator.


![screenshot capture - 2017-06-27 - 13-13-31](https://user-images.githubusercontent.com/17912055/27576441-a0f2e1fc-5b3a-11e7-9579-2dd63997c6f2.png).

* The latent sample is a random vector the generator uses to contruct it's fake images. As the generator learns through training, it figures out how to map these random vectors to recognizable images that can foold the discriminator.

* The output of the discriminator is a sigmoid function, where **0** indicates a **fake image** and **1** indicates an real image.  


# Generator Network

