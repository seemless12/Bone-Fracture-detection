🦴 Bone Fracture Detection with YOLOv8






This project demonstrates Bone Fracture Detection in X-ray images using YOLOv8.
It provides an automated deep learning system that helps doctors and radiologists by detecting fractures with high accuracy and speed, reducing manual workload in clinical diagnosis.

🚀 Features

✅ Detects bone fractures directly from X-ray images.

✅ Built on YOLOv8, one of the most powerful object detection models.

✅ Supports single images, batch processing, and videos.

✅ Generates confidence scores for predictions.

✅ Can be deployed into hospital systems, medical web apps, or research platforms.

📊 Dataset

The dataset consists of labeled X-ray images in two categories:

🟢 Normal Bones

🔴 Fractured Bones

Annotations prepared in YOLOv8 format.

Preprocessing included resizing, normalization, and augmentation for robust performance.

🏋️ Model Training

Model: YOLOv8 (Ultralytics)

Framework: PyTorch

Training with multiple epochs until convergence.

Generated model weights are available for inference on unseen X-rays.

📈 Model Evaluation

The model was evaluated using:

Accuracy

Precision & Recall

mAP (mean Average Precision)

These metrics confirm strong performance in detecting fractures vs. normal bones.

📌 Future Work

📂 Expand dataset with more diverse X-ray samples.

🩻 Add bounding box localization for fracture regions.

🌐 Deploy as a web application for hospitals.

⚡ Experiment with larger YOLOv8 models for higher accuracy.

📜 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute it for research and development.

🔑 Keywords for SEO

bone fracture detection, YOLOv8 X-ray AI, medical deep learning, fracture classification, computer vision healthcare, automated X-ray diagnosis
