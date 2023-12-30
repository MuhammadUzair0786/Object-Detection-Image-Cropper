# Object-Detection-Image-Cropper

Object Detection Image Cropper

Introduction:
This Python-based project utilizes YOLO (You Only Look Once) for object detection in images. It then dynamically crops the image based on the most prominent object detected.

Usage:
Clone the repository.
Install required dependencies: pip install -r requirements.txt
Place your image in the project folder.
Run main.py to execute the cropping process.

Requirements:
Python (3.6 or higher)
OpenCV (cv2)

Project Structure:
main.py: Entry point script.
yolo_module.py: YOLODetector class for object detection.
yolov3.cfg, yolov3.weights, coco.names: YOLO model configurations.

Instructions:
Replace path/to/your/image.jpg in main.py with the actual image path.
Adjust YOLO model configuration files as needed.

Output:
The cropped image will be saved in the project folder.

Note:
Fine-tune confidence thresholds and model parameters in YOLODetector for optimal results.
Ensure YOLO model files are correctly configured.
Feel free to contribute or customize for your specific needs!
