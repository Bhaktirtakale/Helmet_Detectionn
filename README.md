# YOLO Helmet Detection (OpenCV + Google Colab)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ncQaI-1U17oygBlhoKBvlf7wzGLI1Xvg?usp=sharing)

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-informational)
![Status](https://img.shields.io/badge/Works-on%20Colab-brightgreen)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Quick Start (Colab)](#quick-start-colab)
- [Screenshots](#screenshots)
- [How It Works](#how-it-works)
- [Limitations](#limitations)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction
This project demonstrates object detection using a YOLO model with OpenCV, packaged in an easy-to-run Google Colab notebook. No local setup needed—open the notebook, run all cells, and try with your own images or videos.

## Features
- One-click **Open in Colab** workflow
- Detect objects in **images**, **videos**, or **webcam** (if enabled)
- Save detection outputs to files
- Clear, beginner-friendly code blocks and comments

## Quick Start (Colab)
1. Click the **Open in Colab** button at the top.
2. In Colab, go to **Runtime → Run all** (or run cells step-by-step).
3. (Optional) Upload your own images/videos using the left **Files** panel or `from google.colab import files`.
4. Check the notebook cells for:
   - Model download/setup
   - Inference on images/videos
   - Saving results (e.g., `cv2.imwrite('output.jpg', img)`)

> Tip: Keep large weights and videos out of GitHub. Let the notebook download them at runtime or link them externally.

## Screenshots
Results from the Colab notebook:

![Image detection example](assets/output_example.jpg)
<!-- Add more if you have them -->
<!-- ![Video frame example](assets/video_frame.jpg) -->
<!-- ![Realtime demo](assets/realtime_demo.gif) -->

## How It Works
High-level steps:
1. Install dependencies (OpenCV, etc.) inside Colab.
2. Load a pretrained YOLO model (or your fine-tuned weights).
3. Preprocess input → Run inference → Postprocess boxes.
4. Visualize and save outputs.

## Limitations
- Small or overlapping objects may be missed.
- Accuracy depends on model/weights and input resolution.
- GPU availability in Colab may vary over time.

## Project Structure
├── README.md
└── assets/
├── output_image.jpg


## Contributing
Pull requests and suggestions are welcome. Please open an issue to discuss major changes.

## License
This project is released under the MIT License. See [LICENSE](LICENSE) for details.

## Acknowledgments
- YOLO family of models
- OpenCV
- Google Colab

