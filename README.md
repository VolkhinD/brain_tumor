# Brain Tumor

In this work I research medical images which look like grayscale, but this is RGB format images. I compare two CNNs: Resnet-18 and AlexNet, and also play with learning rate schedular
- **1 Approach:** Train whole NOT pretrained models, and apply learning rate schedular so every 5 steps learning rate decreased by 10 times.
- **2 Approach:** Add one more linear layer to pretrained models and train only new one. Use the same learning rate schedular. 
