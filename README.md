# CatGAN Repo

Implemented cyclegan for cat-human transformations, refer to youtube demo for more details.
If you want to set up and train, use google colab, in the files a path is given to images you want to use, either create directory that mathces the path, or rewrite that segment.

We give the cat and human data, but technically you can train on any two domains, although performance will vary because we have designed our models for cat-human transformation. If you are using a different dataset, our models operate on 128x128 images, we resize them but a lot of information is lost during transformation, so choose a dataset that is close to 128x128.

References:
Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks: https://arxiv.org/abs/1703.10593

Thank you, have fun
Thank you authors of original paper, reading and implementing and learning about your research was thrilling
