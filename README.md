# Detection_Classification
This project focuses on waste object classification and detection using multiple deep learning models.
  - Waste Detection using a trained Faster R-CNN model for precise localization.
  - Waste Classification into 4 major categories using custom-trained deep learning models.
## Current Progress
- Achieved ~99% classification accuracy on datasets using multiple models.
- Performed object detection on the TACO dataset with Faster R-CNN and YOLO to localize waste objects producing accurate bounding boxes.
- Pretrained YOLO was tested for general object detection.
- Combined detection with classification for broader category predictions.
Pipeline: Data Collection → Preprocessing → Train Classification Models → Train Detection Models (Faster R-CNN, YOLO) → Detect Objects → Crop & Classify → Evaluate → Improve & Deploy.
## Limitations
Detection + Classification results are moderate due to:
  - Fewer epochs in training
  - Limited dataset size
## Future Work
-  Increase training epochs for both detection and classification models for better accuracy.
-  Apply advanced data augmentation techniques.
-  Fine-tune pretrained detection models on the TACO dataset.
-  Increase the classification dataset size to improve the diversity.
    
