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

## 3. Key Findings
- **YOLOv8:** Highest accuracy and precision. Best for minimizing false positives.
- **YOLOv11:** Fastest training, smallest model size, most efficient for edge devices.
- **YOLOv7:** Strong recall, but resource-heavy and less efficient for deployment.

## 4. Conclusions
- **YOLOv11 is recommended for practical deployments (speed, size, efficiency, balanced accuracy).**
- YOLOv8 preferred for high-accuracy and safety-critical use cases.
- YOLOv7 suitable only for legacy infrastructure or exploratory use where resources are less constrained.
---
  _**Note:** Please note that this project is being made just to form a brief understanding of YOLO and by no means establish research/scholar grade conclusions_

---
## Inferences
- **YOLOv7**
![yolov7_image_result](https://github.com/user-attachments/assets/5aa3833c-7ed3-4e4b-b743-0e1edf2d1d61)
- **YOLOv8**
![yolov8_image_result](https://github.com/user-attachments/assets/13bf9445-af59-4ba3-a840-a6d3f4177319)
- **YOLOv11**
![yolov11_image_result](https://github.com/user-attachments/assets/b172c137-1c07-4d5e-8224-7c2daa386db4)

## Results Curves
- **YOLOv7**
<img width="2400" height="1200" alt="YOLOv7_results" src="https://github.com/user-attachments/assets/9066573d-b010-4292-bdc1-7668cac46693" />

- **YOLOv8**
<img width="2400" height="1200" alt="YOLOv8_results" src="https://github.com/user-attachments/assets/1910f2c6-ff4a-4aea-b2b4-872a48e827d7" />

- **YOLOv11**
<img width="2400" height="1200" alt="YOLOv11_results" src="https://github.com/user-attachments/assets/c5f42a5d-d8a4-4cb5-b68d-a57b201bd9bf" />
