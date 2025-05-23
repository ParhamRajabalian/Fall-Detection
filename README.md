# 🧍‍♂️ Fall Detection with 3D Pose Estimation (Google Colab Ready)

This project performs fall detection from videos using 3D human pose estimation and a deep learning model.

✅ Features:
- Upload a video (MP4 format)
- Extract 3D poses using a trained lifting model
- Run a fall detection model on the sequence
- Output an annotated video with `FALL` or `NO FALL` label overlayed

---

## 🚀 Run on Google Colab

Click the link below to open and run the project in Google Colab:

👉 [Open in Colab](https://colab.research.google.com/github/ParhamRajabalian/UserProjectGRPC/blob/master/Fall_Detection.ipynb)

---

## 📋 How to Use

1. Open the notebook in Colab.
2. Upload your video using the `files.upload()` cell.
3. The `FallDetectionNet` model will be applied to the video.
4. The final output will be a video with overlay labels indicating `FALL` or `NO FALL`.

---

## 📦 Models Required

Ensure the following models are available in the same directory or upload them in Colab:

- `lifting_model.pth`: 3D pose lifting model
- `fall_detection_model.pth`: Trained fall detection model

---

## 🧪 Requirements

The notebook requires the following Python packages:
torch
opencv-python
mediapipe
numpy
yaml
Copy

---

## ✨ Author

Developed by [Parham Rajabalian](https://github.com/ParhamRajabalian).

