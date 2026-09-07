# Lightweight Edge Intelligence for Plant Disease Classification
## Project Introduction
-The project at hand involves the implementation of an AI-based solution for plant disease classification from leaf images with the motivation of obtaining a lightweight model that can be deployed on edge devices.
-The knowledge of a high-accuracy MobileNetV4 teacher model was transferred to a lightweight MobileNetV3 student model using the technique of knowledge distillation.
-The produced lightweight model had its size reduced through post-training INT8 quantization to enable its deployment on resource-constrained devices.
-Besides, the Grad-CAM explanation method was utilized in the project to provide class activation visualization. Overall, this project provides an accurate, lightweight, and explainable solution for plant disease classification from leaf images.

## Summary of Methodology
To achieve the objectives of this project, the following steps were done:
• MobileNetV4 – Teacher model (high accuracy).
• Knowledge Distillation – Transfer learning methodology.
• MobileNetV3 – Student model (lightweight).
• INT8 Quantization – Post-training model size reduction.
• Grad-CAM – Class activation visualization.
• PlantVillage – Dataset for plant disease classification.

## Classification Results
The following table summarizes the results obtained using different models:
ModelTest Accuracy
Baseline MobileNetV397%
MobileNetV498%
Distilled MobileNetV399.5%
The following table summarizes the outcome achieved with the proposed model:
ParameterNumber
Parameters1.53 M
MACs59.9 M
Original Model Size (MB)5.98
Quantized Model Size (MB)4.2
Quantization LevelINT8
Accuracy after Quantization (classification)Accuracy maintained

## Explainability
The Grad-CAM explanation method was employed to produce an overlay of class activation map on the input leaf image to demonstrate the evidence used by the model for disease classification.

## Tools and Technologies
The following tools and technologies were utilized in this project:
• Python
• TensorFlow/Keras
• MobileNetV3
• MobileNetV4
• Knowledge Distillation
• INT8 Quantization
• Grad-CAM
• PlantVillage
• Jupyter Notebook

## Domain of Utilization
The proposed solution can be implemented in the following domains:
• Plant disease detection
• Precision agriculture
• Smart farming
• Edge AI
• Real-time plant disease classification
• Agriculture with limited resources

## Future Scope
The future scope of this project can involve the following:
• Enhance the model to enable its deployment on mobile phones, Raspberry Pi, and other edge devices.
• Perform extensive experimentation to improve the accuracy of the distilled MobileNetV3 model.
• Consider more classes for plant disease classification.
• Optimize the model for faster inference.

## Project Motivation
The motivation of this project was to produce a solution for plant disease classification that is accurate, lightweight, scalable, and explainable.
