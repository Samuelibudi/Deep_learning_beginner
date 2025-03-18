Transfer Learning: Fine-Tuning a Pretrained Model on CIFAR-10
Objective:
Use a pre-trained model (like MobileNetV2) to classify CIFAR-10 images.

Dataset:
CIFAR-10 Dataset

Steps:
Load CIFAR-10 dataset and preprocess images.
Use a pre-trained model (MobileNetV2, ResNet50) and freeze its layers.
Attach a custom classification head with a dense layer.
Train and fine-tune the model using Adam optimizer and categorical cross-entropy.
Evaluate performance on the test set.
Set a target metric: Achieve at least 92% accuracy on CIFAR-10.
