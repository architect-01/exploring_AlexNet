# exploring_AlexNet

Notebooks in this repo explore the thing that started it all - AlexNet(2012).
This was a part of my BSc thesis at School of Electrical Engineering, Belgrade.

Three different training techinques have been used:
- Training the model from scratch (A0 model)
- Using the pretrained model (on ImageNet 2012) with Transfer learning - Feature Extractor (A1 model)
- Using the pretrained model (on ImageNet 2012) with Transfer learning - Fine tunning (A2 model)

# Dataset : https://www.robots.ox.ac.uk/~vgg/data/pets/ .
Dataset consists of 37 different pet races with every class having around 200 pictures.

![images](https://user-images.githubusercontent.com/83124384/117290480-25dfed80-ae6e-11eb-8a96-16f87a271dea.jpeg)

Custom train/val/test split has been used (preproccesing scripts haven't been included) and is available at : https://drive.google.com/drive/folders/1ssJprjTbJQZAeYV8XwowSJPyW3hvZuIN?usp=sharing

Link to the models: https://drive.google.com/drive/folders/1Qa4ZGHhIIZTnaWfDd_9N02zFL7yYWj93?usp=sharing

# Final results:
- Model A0: Test Acc: 0.8096
- Model A1: Test Acc: 0.8440
- Model A2: Test Acc: 0.8575
