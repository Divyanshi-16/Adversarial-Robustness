# Adversarial-Robustness
Deep Learning models are vulnerable to adversarial examples. Adversarial examples are created by making subtle changes in benign dataset. In this sections, I have dealt with white box adversarial attacks, namely FGSM and PGD. This section shows the difference between accuracy, in the case of clean datset training, and training on adversarially attacked dataset. I am working on MNIST dataset.
- I have performed training on clean dataset, on a convolutional neural network model, and one on feed forward model.
- The former gave the accuracy score as 0.9951, precision score as 0.9952, and recall score as 0.9951.
- The latter gave the accuracy score as 0.9868, precision score as 0.9868, and recall score as 0.9867.
- In feed-forward model, after FGSM attack, the accuracy score comes out to be 0.6919, precision score is 0.8650, and recall score is 0.7022.
- After PGD attack, it gives the accuracy score as 0.7688, precision score as 0.8817, and recall score as 0.7814.
## Convolutional Neural Network Model
I have done deep analysis on this model, related to adversatial attacks (FGSM). The following conclusions are: -
- After FGSM white box attack, I got accuracy score as 0.0976, precision score as 0.1136, and recall score as 0.1001.
- I have done a retraining on adversarial examples, and then tested on a clean dataset, accuracy score comes out to be 0.9923, precision score as 0.9925, and recall score as 0.9923.
- Then I have performed retraining on adversarial examples again, and tested on adversarial dataset. Accuracy score comes out to be 0.9929, precision score as 0.2046, and recall score as 0.1562.
## Conclusion
- Adversarial attacks on deep learning models drastically affect model's adversarial robustness.
- Training deep learning models on adversarial examples can definitely improves model's robustness.
