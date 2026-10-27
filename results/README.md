# Results

The final experiments evaluated two deep-learning architectures, ResNet50 and MobileNetV3, for automated finger-count classification.

| Model | Test Accuracy | Weighted Precision | Weighted Recall |
|---|---:|---:|---:|
| ResNet50 | 92.75% | 93.39% | 92.75% |
| MobileNetV3 | 70.00% | 70.10% | 70.00% |

### Findings

ResNet50 achieved a test accuracy of **92.75%**, outperforming MobileNetV3, which achieved **70.00%**. ResNet50 also recorded higher weighted precision (93.39%) than MobileNetV3 (70.10%).

These results indicate that ResNet50 achieved stronger classification performance on the evaluated test set. MobileNetV3 provides a useful comparison with a more lightweight architecture.


### Confusion Matrices

#### ResNet50

![ResNet50 confusion matrix](./images/resnet50_confusion_matrix.png)

#### MobileNetV3

![MobileNetV3 confusion matrix](./images/mobilenetv3_confusion_matrix.png)

