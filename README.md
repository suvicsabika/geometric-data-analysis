# Comparative Geometric Analysis of Object Tracking Algorithms on Video Data

## Project Goal

The objective of this project is to analyze and compare the performance of various object tracking algorithms on real-world video data, with a special focus on the **geometric characteristics of the tracked object trajectories**. Three different models/algorithms are applied to the same input video containing moving objects (e.g., vehicles), and the resulting motion paths are compared in terms of accuracy, stability, and behavioral patterns.

---

## Keywords

`Object Tracking`, `Video`, `Trajectory Analysis`, `Geometric Analysis`, `Bounding Box`, `Computer Vision`, `Deep Learning`

---

## Models Used

- **SORT** (Simple Online Realtime Tracking)  
- **Deep SORT**  
- **YOLOv8 Tracking**

Each model is applied to the same traffic video containing multiple moving objects. The output trajectories (bounding box positions and object IDs) are then analyzed and compared.

---

## Comparison Criteria

| Criteria               | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Tracking Accuracy**  | How consistently the model assigns the same ID to the same object over time |
| **ID Switches**        | Number of times an object is mistakenly assigned a new ID                   |
| **Trajectory Geometry**| Smoothness, length, direction changes, and other geometric features         |
| **Performance**        | Frame-per-second (FPS), runtime, and resource usage (CPU/GPU)               |

---

## Example Input

A video clip showing a traffic scene with moving vehicles (from datasets like ([https://www.kaggle.com/competitions/aicity-2020-track1/data)](https://www.pexels.com/search/videos/traffic/) or similar).

---

## Notebook Structure

- `sort_tracking.ipynb` – Implementation of SORT tracking  
- `deep_sort_tracking.ipynb` – Deep SORT with visual embedding  
- `yolov8_tracking.ipynb` – YOLOv8 built-in tracking API  
- `comparison_analysis.ipynb` – Trajectory comparison and geometric analysis

---

## Notes
May extended the project with a custom object detector (e.g., fine-tuned YOLOv8) for more advanced analysis.
