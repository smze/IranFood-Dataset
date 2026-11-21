## Initial 18-Class Pilot Benchmark

The initial pilot dataset, consisting of 1,903 images across 18 Iranian food classes, was evaluated using three deep learning architectures: ResNet, MobileNet, and EfficientNet-B0.

Experiments were conducted using CPU-based training for up to 10 epochs.

### 1. Benchmark Results

| Model | Best Epoch | Train Accuracy | Val. Accuracy | Train F1 | Val. F1 |
|---|---:|---:|---:|---:|---:|
| ResNet | 10 | 87.04% | 62.48% | 87.03% | 62.01% |
| MobileNet | 8 | 92.12% | 79.29% | 92.12% | 79.11% |
| **EfficientNet-B0** | **5** | **84.53%** | **81.95%** | **84.49%** | **81.86%** |

### 2. Validation Accuracy Across Epochs

| Epoch | MobileNet | ResNet | EfficientNet-B0 |
|---:|---:|---:|---:|
| 1 | 54.69% | 33.63% | 64.07% |
| 2 | 67.61% | 34.34% | 75.22% |
| 3 | 71.50% | 42.48% | 78.41% |
| 4 | 74.51% | 43.36% | 76.11% |
| 5 | 78.23% | 53.27% | **81.95%** |
| 6 | 72.57% | 52.57% | 79.82% |
| 7 | 73.98% | 49.03% | 80.53% |
| 8 | **79.29%** | 59.29% | 79.82% |
| 9 | 71.33% | 50.27% | 78.76% |
| 10 | 74.34% | **62.48%** | 77.35% |

### 3. Key Findings

- **EfficientNet-B0** achieved the best validation accuracy (81.95%) and F1-score (81.86%), with the smallest train–validation accuracy gap (2.58 percentage points).
- **MobileNet** achieved competitive validation performance (79.29% accuracy) and represents a promising lightweight architecture for future deployment evaluation.
- **ResNet** showed a substantially larger train–validation gap (24.56 percentage points), indicating weaker generalization on the pilot dataset.

### 4. Conclusion

EfficientNet-B0 provided the strongest overall validation performance in the initial pilot experiment. These preliminary findings motivated further dataset expansion, improved experimental workflows, and more comprehensive GPU-based model benchmarking.

The subsequent extended experiments are documented separately in the [Extended Benchmarks](../02-extended-benchmarks/README.md) section.
