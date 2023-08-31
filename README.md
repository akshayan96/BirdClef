# BirdClef
BirdClef Competition from Kaggle 2022

In the heart of the "extinction capital of the world," Hawai'i's avian population has been devastated, with a staggering 68% loss in bird species. This ecological crisis has far-reaching consequences, disrupting entire food chains. we will be harnessing machine learning prowess to acoustically recognize bird species through continuous audio data analysis, propelling bioacoustic science, and supporting efforts to safeguard Hawai'ian avifauna. Hopefully, contributions promise more accurate population surveys, better threat assessment, and enhanced conservation strategies, shaping the future of endangered species protection.
We have tried to design networks to process audio data and make predictions about the presence of specific sound events. The model architecture consists of several layers and components, including convolutional layers, attention blocks, and more. It utilizes various techniques like SpecAugmentation for data augmentation and dropout for regularization. The network outputs different types of predictions, including clipwise and framewise outputs.
This model can be used to classify and detect sound events within audio recording. We have compared several models such as ResNet, DenseNet, EfficientNet with less number of layers to accomodate GPU restrictions.
