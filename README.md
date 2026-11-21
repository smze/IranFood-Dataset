# IranFood Dataset

**An Iranian Food Image Dataset for Food Recognition and Nutrition AI Research**

## Overview

IranFood Dataset is a research-oriented project focused on developing a diverse and structured image dataset of Iranian foods for Food Recognition, Computer Vision, and Nutrition AI applications.

The project combines dataset development, benchmarking, and iterative model evaluation to investigate food image recognition under diverse visual conditions.

## Dataset Development

Current Status

- 40 food classes
- Pilot dataset: 1,903 images across 18 classes
- Ongoing dataset expansion and image collection

The dataset is being developed using multiple image sources, including publicly available online images, controlled image acquisition, and user-contributed images.

## Dataset Benchmarking


Established food and nutrition datasets have been studied as references for the development of IranFood Dataset, including:

- Food-101
- Nutrition5k
- Other relevant food and nutrition datasets

The comparative study considers aspects such as dataset structure, class diversity, image characteristics, annotation approaches, and potential applications in food recognition and nutrition estimation.

## Model Benchmarking

The project includes two distinct experimental stages:

### 1. Initial 18-Class Pilot Benchmark

The initial 18-class pilot dataset was evaluated using three deep learning architectures on CPU, with a maximum of 10 training epochs.

| Model               | Best Epoch | Val. Accuracy | Val. F1    | Train Accuracy | Train F1 |
| ------------------- | ---------- | ------------- | ---------- | -------------- | -------- |
| ResNet              | 10         | 62.48%        | 62.01%     | 87.04%         | 87.03%   |
| MobileNet           | 8          | 79.29%        | 79.11%     | 92.12%         | 92.12%   |
| **EfficientNet-B0** | **5**      | **81.95%**    | **81.86%** | 84.53%         | 84.49%   |

These results represent the preliminary benchmark on the 1,903-image, 18-class pilot dataset.

### 2. Extended Dataset and Model Benchmarks

Following the initial pilot study, the dataset management and experimental pipeline were further developed.

The 18-class dataset was re-evaluated using the improved framework, and the dataset was subsequently expanded to 42 classes. The 100-class version is currently under development.

The extended framework includes:

- Four deep learning architectures:
  - EfficientNet-B0
  - ResNet18
  - MobileNetV2
  - Vision Transformer (ViT-B/16)
- ImageNet-pretrained weights
- GPU-based training
- Separate CSV files for training, validation, and test splits
- A maximum of 30 epochs with Early Stopping
- Multiple classification evaluation metrics
- Confusion matrix analysis
- Training time measurement

The original 18-class samples and their split assignments were maintained within the 42-class dataset version, allowing more consistent evaluation across dataset versions.

Detailed experimental configurations and results are documented separately for each dataset version.



## Research Focus

 Current research activities include:

- Dataset design and expansion
- Data quality control
- Image standardization
- Food recognition
- Deep learning model benchmarking
- Generalization and overfitting analysis
- Error analysis
- Nutrition AI
- Multimodal AI
## Current Status

Active Research & Development

Current focus:

- 40-class dataset development
- Dataset expansion and quality control
- Benchmarking against established food datasets
- Deep learning model evaluation
- Preparation for larger-scale experiments and MVP development
## Future Research Directions

Potential research directions include:

- Further dataset expansion
- Real-world image diversity
- Food recognition and segmentation
- Depth and multi-view analysis
- Food volume estimation
- Multimodal food understanding
- Nutrition estimation

Detailed methodology, experimental configurations, and research documentation will be added separately as the project progresses.

## Project Website

A public landing page has been developed to support dataset participation and image collection.

Visit the IranFood Dataset Website: Iranfoodd.ir


## Author

Somayeh Mardani

AI / Machine Learning Engineer & Researcher

Technical Lead & Project Designer — IranFood Dataset

Research interests: Computer Vision · Deep Learning · Multimodal AI · Dataset Development · Food Recognition · Nutrition AI
