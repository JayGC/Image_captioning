# Image_captioning

## Overview
This project focuses on creating an image captioning model based on the encoder-decoder architecture. The primary goal is to generate descriptive captions for images automatically. To achieve this, we have leveraged a pre-trained VGG16 model as an encoder for extracting image features and implemented a feed-forward neural network with LSTM layers as the decoder.
description of images

## Description
### Image Feature Extraction
For effective image feature extraction, we employed the pre-trained VGG16 encoder. This deep convolutional neural network has proven to be highly effective in capturing rich visual features from images. The extracted features serve as the foundation for generating descriptive captions.
### Text Preprocessing
To prepare textual data for feeding into the decoder, we conducted necessary text preprocessing and tokenization. This step ensures that the input data is in the appropriate format for the decoder model. Text preprocessing involves tasks like removing punctuation, lowercasing, and handling special characters.
### Image Data Preprocessing
Prior to feature extraction, image data underwent preprocessing to ensure it was in the correct format. This preparation step is essential for feeding images into the VGG16 encoder. It involves resizing, normalizing, and transforming the images to match the encoder's input requirements.
### Model Evaluation
The performance of our image captioning model was assessed using standard evaluation metrics, including BLEU-1 and BLEU-2 scores. These metrics measure the similarity between generated captions and human-annotated captions. The model achieved a BLEU-1 score of 0.54 and a BLEU-2 score of 0.36. These results indicate the model's capability in capturing both unigrams and bigrams in the generated captions, showcasing its effectiveness in describing image content.

## Dataset
This project utilized the Flickr8k dataset, which is publicly available on Kaggle. The dataset comprises a diverse collection of images with corresponding human-generated captions. You can access the dataset at the following link: [Flickr8k Dataset](https://www.kaggle.com/datasets/adityajn105/flickr8k).


