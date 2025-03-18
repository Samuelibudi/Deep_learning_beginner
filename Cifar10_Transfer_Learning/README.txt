Computer Vision: Image Classification with CNNs (Cats vs. Dogs)
Objective:
Train a CNN to classify images of cats and dogs.

Dataset:
Dogs vs. Cats Dataset

Steps:
Load and preprocess images:
Resize all images to (128x128).
Normalize pixel values.
Split into train/test datasets.
Use data augmentation (rotation, flipping, zoom, etc.).
Build a CNN architecture with Conv2D, MaxPooling, Flatten, and Dense layers.
Train the model using categorical cross-entropy.
Evaluate the model using accuracy.
Set a target metric: Achieve at least 85% validation accuracy.