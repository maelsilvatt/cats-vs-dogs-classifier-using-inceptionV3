# Cats vs. Dogs Classifier Using Transfer Learning with InceptionV3
This is a deep learning project that uses transfer learning to classify images of cats and dogs. The neural network is built on top of the InceptionV3 architecture, which is a popular convolutional neural network used for image classification.

## Dataset
The dataset used for this project is a curated version of the [Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats/data) dataset from Kaggle. It contains 3,000 images of cats and dogs, with 1,500 images in each category. The images are of varying sizes and aspect ratios, and the quality varies from high-quality professional photographs to low-quality camera phone pictures.

## Transfer Learning
Transfer learning is a technique used to transfer knowledge from a pre-trained model to a new model that is being built for a similar task. In this project, we used the pre-trained VGG16 model and added a few layers on top to fine-tune the model for our specific task of classifying images of cats and dogs.

Frozen the weights of the pre-trained layers and trained only the weights of the new layers added on top, allowed us to train the model faster and with less data.

## Results
The model achieved an accuracy of 95.3% on the testing set.

## Acknowledgements
- [Dogs vs. Cats dataset](https://www.kaggle.com/c/dogs-vs-cats/data) from Kaggle
- [InceptionV3](https://keras.io/api/applications/inceptionv3/) model from Keras
License
This project is licensed under the MIT License. See the [LICENSE]() file for details.
