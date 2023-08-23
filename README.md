# CLIP-based models for Image Captioning

**Language:** Python

**Framework:** PyTorch

**Platform:** Jupyter Notebook

**Cloud Service:** Google Colab

## Overview

Image captioning is a challenging task that involves training deep learning models to understand the visual content of an image and generate a corresponding natural language description.

One popular method is to use a CNN for image feature extraction and an RNN for sequence generation. In this paper, two new CLIP-based approaches for image captioning are proposed.

- The first approach is zero-shot prediction, which uses CLIP to detect objects in an image and then converts these objects into a caption using FLAN-T5.
- The second approach fine-tunes the pre-trained language model GPT-2 with the image feature, extracted from the CLIP image encoder, to generate a sequence of words.
- The results show that the CLIP-based methods perform well, with the CLIP+FLAN-T5 model producing comparable captions to the traditional CNN+LSTM model under no training step, and the CLIP+GPT-2 model generates better results with a faster training process.
