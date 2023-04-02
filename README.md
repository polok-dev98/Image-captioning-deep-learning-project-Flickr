# About the project:
A Image Captioning system using the VGG16 and Encoder-Decoder (Keras implementation).Here used Flickr8k image dataset for training the model and predicting the image caption.

Dataset Download link: https://www.kaggle.com/datasets/adityajn105/flickr8k/download

1. Used VGG16 model for extracting the features from the Flickr8k image dataset.

2. Used Keras Tokenizer for tokenized the captions into sequence of integers and model inputs.

3. Building a Encoder-Decoder model using Embeddings , LSTM and Dense layer for training purposes and generate caption using the trained model to given image input.

 You can train the model with data or just use the best_model.h5 pretraind model for prediction.

