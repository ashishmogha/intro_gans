# intro_gans

* In this,we are gonna building a generative adversarial network (GAN) trained on [MNIST](http://yann.lecun.com/exdb/mnist/) dataset.


* In **GANs** is that you have two networks, a **generator G**  and a **discriminator D** , competing against each other. The generator makes fake data to pass to the discriminator. The discriminator also sees real data and predicts if the data it's received is real or fake.
* The **generator** is trained to fool the **discriminator**, it wants to output data that looks as close as possible to real data. And the discriminator is trained to figure out which data is real and which is fake. What ends up happening is that the generator learns to make data that is **indistiguishable** from real data to the discriminator.
