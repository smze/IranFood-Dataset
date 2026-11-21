# IranFood Dataset

**An Iranian Food Image Dataset for Food Recognition and Nutrition AI Research**

## Overview

IranFood Dataset is a research-oriented initiative focused on developing a diverse and structured image dataset of Iranian foods for Food Recognition, Computer Vision, and Nutrition AI applications.

The project combines dataset development, data quality management, deep learning benchmarking, and model evaluation to investigate food recognition across different Iranian food categories and visual conditions.

## Dataset Development

The dataset is being developed through a structured workflow involving image collection, organization, quality control, and dataset expansion.

**Current dataset versions:**

- **18-class:** Initial pilot dataset and subsequent extended benchmark version.
- **42-class:** Expanded dataset containing the original 18 food categories and 24 additional categories.
- **100-class:** Dataset expansion currently undergoing data cleaning and quality control.

Images are collected from multiple sources, including publicly available online images, controlled image acquisition, and user-contributed images.

Dataset development also involves image standardization, annotation management, and consistent train, validation, and test split organization.

## Dataset Benchmarking and Related Work

Established food and nutrition datasets have been studied as references for the design and development of IranFood Dataset, including:

- Food-101
- Nutrition5k
- Other relevant food and nutrition datasets

The comparative study considers dataset structure, class diversity, image characteristics, annotation approaches, and potential applications in food recognition and nutrition estimation.

## Model Benchmarking

Model evaluation has been conducted in two distinct experimental stages.

### 1. Initial 18-Class Pilot Experiment

The initial pilot dataset, consisting of **1,903 images across 18 food classes**, was evaluated using three deep learning architectures.

- Models: ResNet, MobileNet, and EfficientNet-B0
- Hardware: CPU
- Training: Up to 10 epochs
- Best-performing model checkpoints were saved during training.

**Pilot results:**
Detailed experimental configurations and results, including the performance of all three models, are available in the [Initial 18-Class Pilot](experiments/01-initial-pilot-18-class/README.md).

### 2. Extended Dataset and Model Benchmarks

Following the initial pilot, the dataset organization, data management workflow, and experimental pipeline were further developed.

The improved framework was used to re-evaluate the 18-class dataset and subsequently evaluate the expanded 42-class version.

**Experimental framework:**

- Four deep learning architectures:
  - EfficientNet-B0
  - ResNet18
  - MobileNetV2
  - Vision Transformer (ViT-B/16)
- ImageNet-pretrained weights
- GPU-based training
- Separate CSV files for training, validation, and test splits
- Up to 30 training epochs with Early Stopping
- Comprehensive classification evaluation metrics
- Confusion matrix analysis
- Training time measurement

- The shared 18-class samples retain their corresponding train, validation, and test split assignments in the 42-class version, supporting consistency across the extended experiments.

Detailed configurations, evaluation metrics, and visual results are documented separately for each dataset version:

- [18-Class Extended Benchmark](experiments/02-extended-benchmarks/18-class/README.md)
- [42-Class Extended Benchmark](experiments/02-extended-benchmarks/42-class/README.md)

The 100-class dataset is currently undergoing preparation and quality control. Its model benchmarking will be conducted as a separate experimental stage.

## Research Focus

Current research and development activities include:

- Iranian food image dataset design and expansion
- Data collection and quality control
- Image standardization and dataset organization
- Food image classification and recognition
- Deep learning model benchmarking
- Model generalization and overfitting analysis
- Performance evaluation and error analysis
- Nutrition AI and food understanding
- Multimodal AI applications

## Current Status

**Active Research and Development**

Current activities focus on:

- Preparation and quality control of the 100-class dataset
- Maintenance and documentation of the 18-class and 42-class experimental versions
- Deep learning model evaluation and benchmarking
- Analysis of model performance and classification errors
- Development of the research foundation for a nutrition-oriented food recognition MVP

## Future Research Directions

Potential research directions include:

- Further expansion of Iranian food categories
- Improved recognition under real-world imaging conditions
- Multi-label food recognition and food component detection
- Food segmentation
- Depth-based and multi-view image analysis
- Food volume and portion estimation
- Multimodal food understanding
- Nutrition estimation and dietary assessment

Detailed methodology, experimental configurations, and research findings will be documented as the project progresses.

## Project Website

A public landing page has been developed to support dataset participation and image collection.

**Website:** [Iranfoodd.ir](https://iranfoodd.ir)

## Author

**Somayeh Mardani**

AI / Machine Learning Engineer & Researcher

Technical Lead & Project Designer — IranFood Dataset

**Research Interests:** Computer Vision · Deep Learning · Multimodal AI · Dataset Development · Food Recognition · Nutrition AI
