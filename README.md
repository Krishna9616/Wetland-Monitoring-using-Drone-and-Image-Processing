# Wetland-Monitoring-using-Drone-and-Image-Processing

This project focuses on **wetland monitoring** using **drone imagery** and **YOLOv11-based object detection**.  
It aims to detect the aquatic species through aerial image analysis.

---

## 📌 Project Overview

- Collected **aerial drone images** of wetland regions.  
- **Manually annotated** dataset using *LabelImg* to generate bounding boxes for target ecological objects.  
- Applied **data augmentation** (rotation, scaling, brightness, flipping) to improve model generalization.  
- Trained a **custom YOLOv11 model** for object detection and classification on wetland datasets.  
- Evaluated performance on validation data and unseen test images to ensure robustness.

---

## 🧠 Technologies Used

- **Python**
- **YOLOv11**
- **OpenCV**
- **LabelImg**
- **NumPy / Pandas / Matplotlib**

---

## 📊 Model Performance

| Metric | Score |
|---------|--------|
| **Precision (B)** | 0.985 |
| **Recall (B)** | 0.984 |
| **mAP@50 (B)** | 0.990 |
| **mAP@50–95 (B)** | 0.912 |
| **Fitness** | 0.919 |

These metrics demonstrate **high detection accuracy and strong localization performance** on the validation dataset.


