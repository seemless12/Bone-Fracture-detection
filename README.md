🦴 Bone Fracture Detection with YOLOv8

This project focuses on detecting bone fractures in X-ray images using YOLOv8, one of the most powerful object detection models. The goal is to provide an automated system that can assist doctors and medical professionals by quickly identifying whether a bone is fractured or not.

The model has been trained on a dataset of X-ray images, with annotations prepared in YOLO format. It classifies images into two categories: normal bones and fractured bones. By leveraging deep learning, the system ensures fast, accurate, and reliable results that can complement clinical analysis.

🚀 Features

Detects bone fractures directly from X-ray images

Built using YOLOv8 for high-speed and high-accuracy detection

Works on both single images and batches of images

Supports predictions on images, folders, and even videos

Can be easily deployed in real-world medical systems or web apps

📊 Dataset

The dataset consists of labeled X-ray images divided into two classes: fracture and normal. The data was annotated in YOLOv8 format to ensure compatibility with the model training process. Preprocessing steps such as resizing and normalization were applied to improve performance.

🏋️ Model Training

The YOLOv8 model was trained on this dataset with multiple epochs until optimal accuracy and validation metrics were achieved. The training process generated weights that can later be used for inference on unseen X-rays.

📈 Model Evaluation

The trained model was evaluated on a test set. Metrics such as accuracy, precision, recall, and mAP (mean average precision) were used to measure performance. These results highlight the ability of the model to detect fractures reliably.

🔍 Inference

Once trained, the model can be used to make predictions on new X-ray images. It identifies whether the bone is fractured or normal and provides confidence scores for the prediction.

📌 Future Work

Improve detection by expanding the dataset with more diverse X-ray samples

Add localization to highlight the exact fracture region with bounding boxes

Deploy the system as a web application or integrate it into hospital systems

Experiment with larger YOLOv8 models for improved accuracy

📜 License

This project is licensed under the MIT License, making it free and open for use in research and development.
