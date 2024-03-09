# Massachusetts Roads Segmentation with PyTorch

In this project, I have performed road segmentation on the Massachusetts Roads Segmentation dataset using PyTorch. The project consists of the following key steps:

- **Understanding the Dataset**: I have gained an understanding of the Massachusetts Roads Segmentation Dataset and write a custom dataset class for handling image-mask pairs. Additionally, I have applied segmentation domain augmentations to augment both the images and their masks. For this purpose, I have utilized the Albumentations library.

- **Loading a Pretrained Model**: I have loaded a pretrained state-of-the-art convolutional neural network (e.g., Unet) for the segmentation problem using the Segmentation Models PyTorch library.

- **Training Loop**: I have created a train function and an evaluator function to facilitate the training loop. These functions helped me train the model using the training data.

- **Inference**: Finally, I have used the best-trained segmentation model to perform inference on new images, demonstrating the effectiveness of trained model.
