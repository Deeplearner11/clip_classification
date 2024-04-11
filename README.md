# clip_classification
The CLIP (Contrastive Language-Image Pre-training) model, developed by OpenAI, is a multi-modal vision and language model. It maps images and text descriptions to the same latent space, allowing it to determine whether an image and description match. 
![Screenshot 2024-04-11 193532](https://github.com/Deeplearner11/clip_classification/assets/87230145/93aa5052-018d-4862-b80b-21ff58effd68)

Loads the CIFAR-100 dataset containing images with corresponding class labels.
Due to resource constraint used CIFAR-100 dataset but Places365 would be a better datatset to use.
![download](https://github.com/Deeplearner11/clip_classification/assets/87230145/c1276ee0-be44-41ce-b455-cefdf9875f2d)



Uses text descriptions for each image based on the class labels.
Encodes the text descriptions into features.
Computes the probability scores for each image class using the image features and text features.
Visualizes the top predicted classes and their probabilities for each image.
![download (1)](https://github.com/Deeplearner11/clip_classification/assets/87230145/01d1d5cb-a8d2-4cdf-9710-b30931156320)

Used google palm and langchain and prompted the llm to predict whether an image is of outdoors or indoors for PPE detection using the top 5 predicted class labels.
![Screenshot 2024-04-11 194611](https://github.com/Deeplearner11/clip_classification/assets/87230145/fea8b6fd-7e1b-40e5-969e-7abcf42c3d2b)

