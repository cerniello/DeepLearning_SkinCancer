# DeepLearning_SkinCancer
## Binary classification using Convolutional Neural Network
### Michele Cernigliaro

![alt text](https://media.nature.com/m685/nature-assets/nature/journal/v542/n7639/images/nature21056-f4.jpg)

Skin melanoma is one of the deadliest form of skin cancer. It’s caused by skin cells that begin to develop abnormally. The melanoma usually is detected as an appearance of a new mole or change in an existing mole.

Melanomas typically occur in the skin, but it can involves also organs. It’s a type of skin cancer that can spread to other organs in the body.

Deep Learning is the state of the art for Computer vision. It has a lot of potential in the medicine of the future.

In this small project we perform a binary classification task, regnognising wether a mole is a benign one or a malignant one (melanoma), picking a dataset from [Kaggle](https://www.kaggle.com/fanconic/skin-cancer-malignant-vs-benign) with 3297 images (224x224x3) of benignant/malignant moles.


We built two different Convolutional Neural Networks and we see how they acts. We ended up having a model with a good accuracy (0.94 on the test set).

In this repository you can find:

* The notebook which summarize the results (the models have been pre-trained on Google Colab)
* Short presentation (pdf slides)
