# License Plate Detection using Computer Vision and YOLO + OCR

License Plate Detection using Computer Vision and YOLO + OCR is an end-to-end Automatic Number Plate Recognition (ANPR) system designed to automatically identify vehicle license plates and extract their alphanumeric characters from images.

## Project Objective
* To design an automated system that:
* Detects license plates from vehicle images using YOLO
* Extracts the license plate region
* Recognizes alphanumeric characters using OCR
* Displays the detected plate number accurately

## Overall Pipeline
  Input Image

        ↓

YOLO Model (Plate Detection)

        ↓

Crop License Plate

        ↓
        
Image Preprocessing
        
        ↓
        
OCR (Text Recognition)
        
        ↓
        
License Plate Number Output

## License Plate Detection (YOLO)
* YOLO treats license plate detection as an object detection problem
* The model is trained on annotated datasets (e.g., Roboflow License Plate Dataset)
#### Advantages:
* High speed
* Accurate detection
* Works in real time

## License Plate Recognition (OCR)
### OCR Workflow:
* Convert plate image to grayscale
* Apply thresholding for better contrast
* Resize image to improve text clarity
* Pass processed image to OCR engine
#### OCR Options:
* Tesseract OCR → Lightweight, fast
* EasyOCR → Deep-learning based, higher accuracy for plates

## What the Notebook Covers:
1. Installation & Setup
2. Download Roboflow Dataset (automated)
3. Traditional CV Detection (OpenCV baseline)
4. Train YOLOv8 Model (quick & full training)
5. Model Validation (metrics & visualization)
6. OCR Integration (Tesseract setup)
7. Complete Pipeline (YOLO + OCR together)
8. Batch Processing & Analytics
9. Model Export (ONNX/TFLite/OpenVINO)
10. Train YOLOv8 Model with small and medium YOLO model (Accurate Result)

## Download the Roboflow Dataset:
https://universe.roboflow.com/roboflow-universe-projects/license-plate-recognition-rxg4e/dataset/11
*For downloading the robolow dataset you have to Sign in with your account.*
