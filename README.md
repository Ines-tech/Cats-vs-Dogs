# Cats-vs-Dogs

Description and objective: This was a computer vision group project in python, where the goal was to explore CNNs for the classification of cats vs dogs using Keras.

Used language: Python.

Split of the data: 70% for training and 30% for validation.

Concepts or models explored:
1. VGG with 1, 2 and 3 blocks: With the increase in the number of VGG blocks there was an increase in accuracy, but with overfitting of the data starting at around 5 epochs.
2. Regularization techniques (dropout and data augmentation): To try to adress overfitting a few regularization tecniques were applied to VGG3. Data augmentation allowed better results with no overfitting and with an increase in accuracy. 
3. Transfer learning (VGG16 and ResNet50): Both models showed high values of accuracy (almost 100%) but with severe overfitting.


Conclusion:
While the primary goal of this project was to explore various CNN architectures and techniques, if a model had to be chosen, VGG3 with data augmentation would be preferred. This model achieved an accuracy of approximately 86% without overfitting. Although VGG16 and ResNet50 shoud high accuracy values (almost 100%), they suffered from severe overfitting, which could potentially be addressed with regularization techniques.

