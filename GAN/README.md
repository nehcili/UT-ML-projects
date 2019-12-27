# GAN
based on http://www.cs.toronto.edu/~rgrosse/courses/csc421_2019/assignments/assignment4.pdf

##  Deep Convolutional 
- This is a deep convolutional GAN which generate Windows (or Apple) emojis in pytorch
- discriminator is a deep CNN
- generator is made of layers of transpose convolutional 
- loss function uses L^2 loss instead of log loss


## Cycle GAN
- Using cycle GAN to translate between windows and Apple emojis
- architecture consists of 2 pairs of generator and discriminator based convolutional layers. Follows that of "Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks" by Zhu et al.
- the loss function uses L^2 loss instead of log loss