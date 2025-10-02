
This project implements a **CentroidTracker** class, a fundamental, lightweight algorithm used for tracking objects in video streams by associating new object detections (bounding boxes) across consecutive frames.

The core principle is simple: it assigns a unique ID to each object and tracks it by matching the distance between its stored **centroid** (center point) and the centroids of newly detected bounding boxes.

## 🛠️ Prerequisites

This script requires the following standard Python libraries:

```bash
pip install numpy scipy
