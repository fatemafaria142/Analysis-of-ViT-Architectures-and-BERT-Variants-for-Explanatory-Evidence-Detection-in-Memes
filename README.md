# Analysis of ViT Architectures and BERT Variants for Explanatory Evidence Detection in Memes
This project aims to mine contextual information related to memes by leveraging advanced models for image and text feature extraction. The goal is to succinctly explain the background and context of a meme based on a related document.

## Overview

The objective of this project is to utilize state-of-the-art models for both image and text processing to extract features from memes and associated documents. By employing Vision Transformer architectures (Vision Transformer, Swin Transformer, Swift Transformer) for image feature extraction and BERT variants (mBERT, DistilBERT, XLM-Roberta) for text feature extraction, the project combines both modalities using Late Fusion and a custom classifier.

## Dataset

I utilized the [MEMEX Meme Evidence Dataset](https://github.com/LCS2-IIITD/MEMEX_Meme_Evidence?tab=readme-ov-file) for training and evaluation. This dataset contains annotated memes along with related documents to aid in mining explanatory evidence for memes.

## Methodology

### Feature Extraction
- **Image Feature Extraction:** I employed Vision Transformer models (Vision Transformer, Swin Transformer, Swift Transformer) using Hugging Face's library for image feature extraction.
- **Text Feature Extraction:** BERT variants (mBERT, DistilBERT, XLM-Roberta) were utilized with Hugging Face's library for text feature extraction.

### Fusion and Classification
- **Late Fusion:** The extracted features from image and text modalities were concatenated for multimodal representation.
- **Custom Classifier:** A custom classifier was employed to mine the context that succinctly explains the background of the meme.

