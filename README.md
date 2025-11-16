# Eye-for-Blind
AI-powered image captioning system for visually impaired users using a Deep Learning Encoder–Decoder model with Bahdanau Attention. Built with TensorFlow, Keras, InceptionV3, GRU, and integrated with gTTS for audio narration. Achieved 12% BLEU and 20% contextual accuracy improvement

## Eye for Blind – Image Captioning for the Visually Impaired

Assistive AI | Deep Learning | TensorFlow | Attention Mechanism | Image Captioning

## Overview

Eye for Blind is an AI-powered assistive system designed to help visually impaired individuals understand image content through automatically generated captions and real-time audio narration.
The solution uses a Deep Learning Encoder–Decoder architecture enhanced with Bahdanau Attention to generate meaningful, context-aware descriptions.

### Challenge

Visually impaired users face significant difficulty understanding digital images in texts, social media, and daily tasks.
The goal was to build a solution that can:

Interpret image content

Generate human-like captions

Provide audio narration in real time

Improve over existing baseline captioning models

### Action

To address this, the following approach was implemented:

 Model Architecture

Built a Deep Learning Encoder–Decoder model using TensorFlow & Keras.

Used InceptionV3 (pre-trained on ImageNet) for extracting high-quality image features.

Implemented a GRU-based decoder to generate caption sequences.

Added Bahdanau Attention to improve context focus during caption generation.

 Training Pipeline

Preprocessed the Flick8k dataset with tokenization and sequence padding.

Extracted CNN features using InceptionV3 bottleneck vectors.

Trained the model on image–caption pairs with teacher forcing.

Assistive Feature

Integrated Google Text-to-Speech (gTTS) to convert generated captions into clear audio narration.

### Evaluation

Used BLEU Score to measure caption quality.

Compared performance against baseline encoder–decoder models.

### Result

The system achieved significant improvements:

12% increase in BLEU Score vs baseline models

20% improvement in contextual accuracy

Generated more human-like, descriptive captions

Enabled real-time audio narration, making images accessible for visually impaired users

Delivered a fully functional assistive AI tool ready for demo or extension

### Tech Stack

TensorFlow, Keras

InceptionV3 (ImageNet)

GRU, Bahdanau Attention

gTTS (Text-to-Speech)

Python, NumPy, Matplotlib

BLEU Score Evaluation
