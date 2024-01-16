# Visual Question Answering with Multimodal Transformers

This repo contains the dataset & code for exploring multimodal fusion-type transformer models for the task of visual question answering using linear fusion and bilinear fusion.

## Dataset Used: 
[DAQUAR Dataset](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/vision-and-language/visual-turing-challenge/)

### Models for Experimentation:

- Text Transformers (for encoding questions):
    - RoBERTa: `'roberta-base'`
    - DistilroBERTa: `'distilroberta-base'`
- Image Transformers (for encoding images):
    - DeiT (Data-Efficient Image Transformer): `'facebook/deit-base-distilled-patch16-224'`
    - BEiT (Bidirectional Encoder representation from Image Transformers): `'microsoft/beit-base-patch16-224-pt22k'`


