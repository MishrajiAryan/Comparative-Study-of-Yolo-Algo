# Comparative Study of YOLO Algorithms

A single-page comparative analysis of YOLOv7, YOLOv8, and YOLOv11 object detection algorithms. All models were trained on the Top-View Vehicle Dataset using a Tesla T4 GPU in Google Colab.

## 1. Experimental Setup
- **Hardware:** Tesla T4 14.74GB GPU, 2-core CPU, 12.67GB RAM
- **Platform:** Google Colab
- **Dataset:** Top-View Vehicle Detection (Batch Size: 16)

## 2. Performance Metrics Comparison
| Model   | mAP50   | mAP50-95 | Precision | Recall  | F1-Score | Params     | Size   |
| ------- | ------- | -------- | --------- | ------- | -------- | ---------- | ------ |
| YOLOv7  | 0.969   | 0.716    | 0.898     | 0.941   | 0.919    | 37.2M      | 75MB   |
| YOLOv8  | 0.9714  | 0.7254   | 0.9283    | 0.9252  | 0.9267   | 3.0M       | 5.96MB |
| YOLOv11 | 0.9694  | 0.7156   | 0.8978    | 0.9413  | 0.9191   | 2.6M       | 5.21MB |

_(Leave space for graphs and metric visualizations)_

## 3. Key Findings
- **YOLOv8:** Highest accuracy and precision. Best for minimizing false positives.
- **YOLOv11:** Fastest training, smallest model size, most efficient for edge devices.
- **YOLOv7:** Strong recall, but resource-heavy and less efficient for deployment.

## 4. Conclusions
- **YOLOv11 is recommended for practical deployments (speed, size, efficiency, balanced accuracy).**
- YOLOv8 preferred for high-accuracy and safety-critical use cases.
- YOLOv7 suitable only for legacy infrastructure or exploratory use where resources are less constrained.

---

## 📊 _Insert graphs and inference result images here_

(Add your Jupyter notebook and graphs below this section for full demonstration.)
