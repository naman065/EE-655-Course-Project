
# EE‑655 Course Project: Complex YOLO

**Course**: EE‑655 – Computer Vision & Deep Learning  

---

## 🔍 Overview

This repository presents the implementation of a YOLO-based object detection system adapted for complex-valued input. The project is a part of the EE‑655 course curriculum and explores how complex data representations can influence model performance compared to traditional real-valued inputs.

---

## 📁 Repository Structure

- `Complex YOLO Implementation.ipynb` – Core notebook implementing complex-input YOLO model.
- `Implementation_Demo.ipynb` – Notebook demonstrating inference results using trained models.
- `Course_Project.ipynb` – End-to-end pipeline integrating data preprocessing, training, and evaluation.
- `LICENSE` – MIT License for open-source use.
- `README.md` – Project description and usage guide (this file).

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/naman065/EE-655-Course-Project.git
cd EE-655-Course-Project
```

### 2. Install Dependencies

Make sure Python 3.7+ is installed. Then install the necessary libraries:

```bash
pip install torch torchvision numpy matplotlib opencv-python
```

Other common tools like `scikit-learn` or `tqdm` may also be required depending on notebook usage.

### 3. Run the Notebooks

Open JupyterLab or Jupyter Notebook and run:

- `Complex YOLO Implementation.ipynb` to train and evaluate the complex-valued model.
- `Course_Project.ipynb` to follow the complete workflow.
- `Implementation_Demo.ipynb` to visualize model inference.

---

## ⚙️ Project Workflow

1. **Data Preprocessing**  
   - Load and format dataset.
   - Generate both real and complex input representations.

2. **Model Training**  
   - Implement YOLO architecture.
   - Train on complex-valued and real-valued input data.

3. **Evaluation**  
   - Assess model accuracy using standard metrics (e.g., mAP, IoU).
   - Compare performance of complex vs. real input pipelines.

4. **Inference & Visualization**  
   - Visualize detection outputs on test images.
   - Observe qualitative and quantitative differences.

---

## 📚 References

- EE‑655 Lecture Slides & Notes  
- YOLOv5 Documentation – [https://github.com/ultralytics/yolov5](https://github.com/ultralytics/yolov5)  
- Research papers on complex-valued neural networks and object detection

---

## Contributors

| Name           | Roll No     |
|----------------|-------------|
| Ayush Badgujar | 230259     |
| Ashish Kumar Jha   | 230227   |
| Naman Mohan Singh  | 230678     |
| Prasun Shrivastav  | 230778      |

---
