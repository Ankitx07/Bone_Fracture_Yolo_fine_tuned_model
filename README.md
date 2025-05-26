# Bone_Fracture_Yolo_fine_tuned_model
YOLOv8n is fine-tuned to the bone fracture image-based dataset, which finds and classifies different kinds of bone injuries. 

Dataset link - https://www.kaggle.com/datasets/orvile/human-bone-fractures-image-dataset-hbfmid

Bone Fracture Detection Using YOLOv8
Bone fractures are one of the most common injuries diagnosed using radiographic imaging. However, manual analysis of X-ray images can be time-consuming, subjective, and error-prone, particularly when dealing with subtle fractures or when radiologists are under time constraints. This project presents an AI-based solution to automate the detection of bone fractures using YOLOv8 (You Only Look Once version 8)—a state-of-the-art object detection algorithm.

This model is fine-tuned on a custom-labeled dataset of bone X-ray images, focusing on the localization of fracture regions. By leveraging the capabilities of YOLOv8, the system can process images in real time, identify the presence of a fracture, and highlight it with bounding boxes. The goal is to provide a reliable tool that supports radiologists by improving detection speed, reducing diagnostic errors, and enabling pre-screening in resource-limited settings.

This implementation uses transfer learning, where a pretrained YOLOv8 model is retrained (fine-tuned) on a domain-specific dataset consisting of annotated X-ray images. The annotations specify the presence and location of fractures, allowing the model to learn relevant patterns specific to bone injury detection.

Key Features:

      Real-time detection of fractures in bone X-ray images.
      
      Single-class object detection targeting ‘Fracture’ regions.
      
      High detection accuracy and robustness with minimal false positives.
      
      Built using Ultralytics YOLOv8 framework for efficient training and inference.
      
      Dataset managed and annotated using Roboflow.

Use Cases:
      Automated pre-screening in medical diagnostics.
      
      Assisting radiologists in emergency and trauma care.
      
      Mobile or web-based applications for field and rural health settings.
      
      Medical training and research.


NOTE - The model could not be trained for longer epochs due to hardware limitations. hence, the accuracy of the model is accordingly. 
