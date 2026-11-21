
# Extended Dataset and Model Benchmarks

This section documents the progressive development of the Iranian Food Image Dataset and the systematic evaluation of deep learning models.

Unlike the initial 18-class pilot experiment, this phase uses an improved experimental pipeline with structured dataset splits and comprehensive model evaluation.

## Dataset Versions

- 18-Class Dataset
- 42-Class Dataset
- 100-Class Dataset (in progress)

## Experimental Framework

- Four deep learning architectures:
  - EfficientNet-B0
  - ResNet18
  - MobileNetV2
  - Vision Transformer (ViT-B/16)
- ImageNet-pretrained weights
- GPU-based training
- Separate Train, Validation, and Test CSV files
- Maximum of 30 epochs with Early Stopping
- Multiple classification metrics
- Confusion matrix analysis
- Training time measurement

## Dataset Versioning

The 18-class dataset and its split assignments are preserved within the 42-class dataset version.

The 100-class dataset is planned to extend the 42-class version while maintaining the existing image and split structure for shared samples.

Detailed results and experimental protocols are documented separately for each dataset version.
