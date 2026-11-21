
## Initial 18-Class Pilot Benchmark

The initial 18-class pilot dataset was evaluated using three deep learning architectures:

- ResNet
- MobileNet
- EfficientNet-B0

The experiments were conducted using CPU-based training, with a maximum of 10 epochs.

### Pilot Benchmark Results

| Model | Best Epoch | Val. Accuracy | Val. F1 | Train Accuracy | Train F1 |
|---|---:|---:|---:|---:|---:|
| ResNet | 10 | 62.48% | 62.01% | 87.04% | 87.03% |
| MobileNet | 8 | 79.29% | 79.11% | 92.12% | 92.12% |
| **EfficientNet-B0** | **5** | **81.95%** | **81.86%** | **84.53%** | **84.49%** |

These results represent the initial benchmark conducted on the 1,903-image, 18-class pilot dataset. EfficientNet-B0 achieved the highest validation accuracy and F1-score among the three evaluated models.
