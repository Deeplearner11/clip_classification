# clip_classification
The CLIP (Contrastive Language-Image Pre-training) model, developed by OpenAI, is a multi-modal vision and language model. It maps images and text descriptions to the same latent space, allowing it to determine whether an image and description match. 
![Screenshot 2024-04-11 193532](https://github.com/Deeplearner11/clip_classification/assets/87230145/93aa5052-018d-4862-b80b-21ff58effd68)

Loads the CIFAR-100 dataset containing images with corresponding class labels.
Due to resource constraint used CIFAR-100 dataset but Places365 would be a better datatset to use 
Uses text descriptions for each image based on the class labels.
Encodes the text descriptions into features.
Computes the probability scores for each image class using the image features and text features.
Visualizes the top predicted classes and their probabilities for each image.
Used google palm and langchain and prompted the llm to predict whether an image is of outdoors or indoors for PPE detection using the top 5 predicted class labels.
