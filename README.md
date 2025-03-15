# Visual Question Answering (VQA)

Authors: Abdul Rafay, Shahram Ali

## Overview

This repository contains the implementation of a Visual Question Answering (VQA) system, which integrates image processing and natural language processing (NLP) to answer questions related to images. The system extracts visual features using computer vision techniques and analyzes questions using NLP methods to provide accurate responses.

## Features

- Processes images and textual queries simultaneously.
- Uses VILT (Vision and Language Transformer) for multimodal learning.
- Provides textual answers to questions based on image content.

## System Workflow

1. **Input**: User provides an image and a question.
2. **Image Processing**: Extracts objects, textures, and spatial relationships.
3. **NLP Processing**: Tokenizes and analyzes the semantic meaning of the question.
4. **Multimodal Fusion**: Integrates extracted visual features and textual representation.
5. **Output**: Generates a relevant answer to the question.

## Model Selection

The **VILT (Vision and Language Transformer)** model was chosen due to its effectiveness in capturing complex visual features and semantic relationships.
This model helps understand both images and text queries simultaneously.

## Implementation Details

- Fine-tuned VILT for image feature extraction and question analysis on the dandelin/vilt-b32-mlm dataset available of HuggingFace.
 
### Prerequisites

- Python 3.8+
- PyTorch
- Transformers

## References

- [Aishwarya Agrawa, 2015] VQA: Visual Question Answering
- [Yeongjae Cho, 2024] Pretraining Vision-Language Model for Difference Visual Question Answering
- [Ana Cláudia Akemi Matsuki de Faria, 2023] Survey on VQA Techniques

