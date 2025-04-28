# Image-to-Text-Translation

This project focuses on text-to-image translation by combining image feature extraction and a custom sequence generation model. We first use a pre-trained InceptionV3 network to extract high-level feature representations from images. These extracted features are then used to train a custom Encoder-Decoder model with an Attention mechanism, which learns to generate image features conditioned on the given text inputs.

The Encoder processes the image features, the Attention module helps the Decoder focus on relevant spatial regions, and the Decoder generates the output based on the encoded text and image features. This pipeline allows the model to effectively learn the mapping between textual descriptions and visual representations.

