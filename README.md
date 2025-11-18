# 🚁 Classical Computer Vision for Drone Tracking

This repository contains a Jupyter Notebook (`cv.ipynb`) that demonstrates the application of **classical computer vision (CV) techniques** for real-time object tracking, specifically targeting the challenge of tracking small, fast-moving aerial targets like **drones**.

The project uses the powerful and efficient **OpenCV** library to implement filtering, feature detection, and the high-speed **MOSSE** (Minimum Output Sum of Squared Error) tracker.

## 🎯 Project Overview and Goal

The primary goal is to provide a practical example of a computationally lightweight tracking solution suitable for surveillance or resource-constrained embedded systems. We achieve this by:

1.  Preprocessing video frames to enhance visibility of the target.
2.  Implementing classic feature detection methods.
3.  Deploying the MOSSE tracker for robust, high-frame-rate tracking of the selected target (the drone).

## 🛠️ Requirements

To run the notebook, you need Python and the following libraries:

```bash
pip install opencv-python
pip install opencv-contrib-python  # Required for legacy trackers like MOSSE
pip install matplotlib# computer-vision
