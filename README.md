## 🎥 Synthetic Data Generation for Industrial Object Detection

This project presents a synthetic-to-real data generation pipeline for **Unsupervised Domain Adaptation (UDA)** in industrial object detection. The synthetic dataset was created in **Blender** to simulate the loading system of a laser tube cutting machine.

### Overview

The pipeline automatically generates realistic synthetic images by:

- 📦 Importing industrial CAD models (`.stl` or `.obj`)
- 🎨 Assigning customizable steel materials
- 💡 Configuring realistic lighting (Point and Sun lights)
- 📷 Placing a camera on a **Bezier Circle** to capture the object from multiple viewpoints
- 🎬 Rendering rotating image sequences
- 🏷️ Automatically generating object annotations using Blender's labeling tools
- ⚙️ Managing the entire scene through a JSON configuration file for reproducible dataset generation

The generated synthetic dataset serves as the **source domain**, while real industrial images are used as the **target domain** for unsupervised domain adaptation.

### Features

- Blender-based synthetic dataset generation
- Automatic multi-view rendering
- Configurable lighting and materials
- CAD model support (`.stl`, `.obj`)
- JSON-based scene configuration
- Automatic annotation generation
- Designed for synthetic-to-real domain adaptation research

---

## 🎬 Demo Video

A complete demonstration of the synthetic data generation pipeline is available on LinkedIn.

👉 **Watch the demo here:**

**🔗 https://www.linkedin.com/feed/update/urn:li:activity:7458692245517455361/**

or click below:

[![LinkedIn Demo](https://img.shields.io/badge/Watch-Demo_on_LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/feed/update/urn:li:activity:7458692245517455361/)

---

### Pipeline

```
CAD Model (.stl/.obj)
        │
        ▼
 Import into Blender
        │
        ▼
 Material Assignment
        │
        ▼
 Lighting Configuration
        │
        ▼
 Bezier Circle Camera Animation
        │
        ▼
 Multi-view Rendering
        │
        ▼
 Automatic Annotation
        │
        ▼
 Synthetic Dataset
        │
        ▼
 Source Domain for UDA
```
