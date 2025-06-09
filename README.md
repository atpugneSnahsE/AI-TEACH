# AI-Teach Dataset

The **AI-Teach** dataset is curated for training and evaluating computer vision models, particularly in the field of object detection and educational automation. This dataset is currently in development and will be continuously updated.

## 📦 Dataset Contents (Current Version)

- ✅ **Images**: A full collection of raw image data (JPEG/PNG format).
- ✅ **Sample Annotations (JSON)**: A portion of the dataset has been annotated and provided in JSON format following a standard object detection schema.
- 🔜 **YOLO Format Annotations**: YOLO-compatible labeled data will be uploaded in a future update.
- 🔗 Unlabelled images can be found at : [https://drive.google.com/drive/folders/1zkKrnNhqGXWmDWODAl8tjvBZho7wO4ZA?usp=sharing]

## 🧾 Annotation Format

Currently, annotations are provided in a **custom JSON format** containing:
- `filename`: Image filename.
- `width`, `height`: Image dimensions.
- `annotations`: List of objects with:
  - `label`: Class name.
  - `bbox`: Bounding box coordinates in `[x_min, y_min, width, height]` format.

**Example:**
```json
{
  "filename": "image_001.jpg",
  "width": 640,
  "height": 480,
  "annotations": [
    {
      "label": "student",
      "bbox": [120, 85, 100, 200]
    },
    {
      "label": "teacher",
      "bbox": [300, 100, 90, 180]
    }
  ]
}
```
## 🚧 Work in Progress
We are actively working on:

- 🔄 Completing annotations for all images.

- 🔁 Converting labels to YOLO format.

- 🗂️ Expanding class definitions and metadata.

## 📜 License
This dataset is intended for research and educational purposes only. 

## 🤝 Contributions
We welcome contributions and feedback. Please open an issue or pull request if you'd like to contribute to the dataset or annotation formats.
