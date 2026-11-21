# 18-Class Dataset — Extended Benchmark

## 1. Overview

This experiment evaluates the 18-class Iranian food image dataset using an extended and standardized deep learning benchmarking pipeline.

Unlike the initial pilot experiment, this stage uses a structured dataset organization, separate training, validation, and test splits, GPU-based training, and a broader set of evaluation metrics.

## 2. Dataset Configuration

| Property | Description |
|---|---|
| Number of classes | 18 |
| Total images | 2,034 |
| Training images | 1,424 |
| Validation images | 308 |
| Test images | 302 |
| Data split | Train / Validation / Test |
| Split format | Separate CSV files |

## 3. Experimental Setup

Four pretrained deep learning architectures were evaluated:

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

The following table summarizes the reported classification performance.

| Model | Accuracy | Macro Precision | Macro Recall | Macro F1 | Weighted F1 |
|---|---:|---:|---:|---:|---:|
| EfficientNet-B0 | **92.05%** | **92.12%** | 91.86% | **91.80%** | **92.06%** |
| ViT-B/16 | 91.72% | 92.05% | **91.94%** | 91.66% | 91.68% |
| MobileNetV2 | 88.74% | 89.12% | 88.55% | 88.51% | 88.78% |
| ResNet18 | 88.41% | 89.01% | 88.36% | 88.22% | 88.44% |

## 5. Key Findings

- EfficientNet-B0 achieved the highest overall accuracy and Macro F1-score among the evaluated models.
- ViT-B/16 achieved competitive performance, with the highest Macro Recall.
- All four architectures were evaluated using the same dataset version and split framework.

## 6. Evaluation Artifacts

The following evaluation artifacts are part of the experimental analysis:

- Classification performance metrics
- Confusion matrix visualizations
- Training and validation performance records
- Model training time measurements

Selected evaluation figures and additional experimental details may be added in future updates.

## 7. Reproducibility and Data Availability

The dataset is maintained separately from the public experimental documentation.

The public repository focuses on dataset documentation, experimental methodology, and aggregated benchmark results. Access to the complete dataset and additional research materials may be subject to the relevant data-sharing and research policies.

---

**Note:** These results belong to the extended GPU-based benchmark and must be distinguished from the initial 18-class pilot experiment.

