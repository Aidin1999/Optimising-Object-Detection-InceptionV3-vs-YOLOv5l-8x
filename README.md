# Optimising Object Detection: InceptionV3 vs YOLOv5/YOLOv8x

Hi,I’m **Aidin Miralmasi**, a data scientist and AI engineer passionate about computer vision, cloud-based pipelines, and real-world applications of machine learning. This project is a hands-on demonstration of how deep learning models behave under different architectures and preprocessing workflows., and this project is focused on evaluating the performance of different object detection models—specifically **InceptionV3** and **YOLOv5/YOLOv8x**—for detecting people in diverse image conditions.

The objective is to compare classical CNN-based architectures (InceptionV3) against state-of-the-art real-time detectors (YOLOv5/8x) in terms of accuracy, speed, and generalisation, using a consistent and well-augmented dataset.

---

## 📦 Dataset: *People Detection (General)*

The dataset used in this project is **People Detection (General)** from [Roboflow Universe](https://universe.roboflow.com/mohamed-traore-2ekkp/people-detection-general), published by **Mohamed Traore**. It includes:

- **20,598 images** of people with bounding box annotations
- Preprocessed to **640x640** resolution
- Label format: **YOLOv3 Darknet**
- Data augmentations applied:
  - Horizontal flip (50%)
  - Random cropping (0–20%)
  - Rotation (±10°)
  - Brightness & exposure shift (±15%)
  - Gaussian blur (up to 0.5 px)

---

## 📁 Raw Data Access

Due to GitHub’s 100MB file limit, the dataset is split into 11 parts and placed inside the `raw data/` folder.

```php
raw data/
├── People Detection -General-.v8i.darknet.part01.rar
├── ...
└── People Detection -General-.v8i.darknet.part11.rar
```

To extract:

1. Download **all 11 `.rar` parts**
2. Open `part01.rar` using WinRAR or 7-Zip
3. Extract the contents — all other parts will automatically be combined

---

## 📜 License & Attribution

This dataset is shared under the **Creative Commons Attribution 4.0 (CC BY 4.0)** license.

**Author**: [Mohamed Traore](https://universe.roboflow.com/mohamed-traore-2ekkp)  
**Source**: [https://universe.roboflow.com/mohamed-traore-2ekkp/people-detection-general](https://universe.roboflow.com/mohamed-traore-2ekkp/people-detection-general)  
**Date Exported**: 16 September 2023

### 📖 Citation (BibTeX):
```bibtex
@misc{people-detection-general_dataset,
  title = { People Detection (General) Dataset },
  type = { Open Source Dataset },
  author = { Mohamed Traore },
  howpublished = { \url{ https://universe.roboflow.com/mohamed-traore-2ekkp/people-detection-general } },
  journal = { Roboflow Universe },
  publisher = { Roboflow },
  year = { 2025 },
  month = { jul },
  note = { visited on 2025-07-22 },
}
