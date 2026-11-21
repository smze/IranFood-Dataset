# 42-Class Dataset — Extended Benchmark

## 1. Overview

This experiment evaluates the expanded 42-class Iranian food image dataset using the extended deep learning benchmarking framework.

The 42-class version includes the original 18 food classes and 24 additional classes, extending the dataset's food-category coverage.

## 2. Dataset Configuration

| Property | Description |
|---|---|
| Number of classes | 42 |
| Total images | 4,654 |
| Training images | 3,259 |
| Validation images | 705 |
| Test images | 690 |
| Data split | Train / Validation / Test |
| Split format | Separate CSV files |

The original 18-class samples and their corresponding split assignments were maintained in the expanded dataset version, subject to dataset cleaning and version-specific data changes.

## 3. Experimental Setup

The following pretrained architectures were evaluated:

- EfficientNet-B0
- ResNet18
- MobileNetV2
- Vision Transformer (ViT-B/16)

Experimental configuration:

- Pretrained weights: ImageNet
- Training hardware: GPU (CUDA)
- Maximum training epochs: 30
- Early Stopping: Applied
- Model evaluation: Validation and test sets
- Evaluation outputs: Classification metrics and confusion matrices

## 4. Benchmark Results

| Model | Accuracy | Macro Precision | Macro Recall | Macro F1 | Weighted F1 |
|---|---:|---:|---:|---:|---:|
| EfficientNet-B0 | **84.78%** | **85.50%** | **84.69%** | **84.30%** | **84.37%** |
| ResNet18 | 83.04% | 83.29% | 82.83% | 82.17% | 82.33% |
| MobileNetV2 | 82.61% | 83.26% | 82.54% | 82.42% | 82.51% |
| ViT-B/16 | 80.72% | 81.53% | 80.71% | 80.11% | 80.18% |

## 5. Key Findings

- EfficientNet-B0 achieved the highest accuracy and Macro F1-score among the four evaluated architectures.
- The expanded dataset provides a more challenging classification setting with 42 food categories.
- The benchmark provides a basis for evaluating model performance as the dataset grows.

## 6. Evaluation Artifacts

The experimental analysis includes:

- Classification performance metrics
- Confusion matrix visualizations
- Training and validation performance records
- Model training time measurements

Selected figures and additional experimental details may be added in future updates.

## 7. Reproducibility and Data Availability

The dataset is maintained separately from the public experimental documentation.

The public repository focuses on dataset documentation, experimental methodology, and aggregated benchmark results. Access to the complete dataset and additional research materials may be subject to the relevant data-sharing and research policies.

---

**Note:** These results belong to the extended GPU-based benchmark and are distinct from the initial 18-class pilot results.

