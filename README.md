# DOCUMENTATION
<details>
  <summary> INSTALL(Python 3.8) </summary>

  ```sh
  git clone github.com/Anikcb/Waste-Segregation
  cd Waste-Segregation
  pip install -r requirements.txt
  ```
</details>

## Introduction
we are proposing a hybrid wastage classification and management system using DL and ML with other IoT devices. We are also proposing a reward-giving policy via our website to encourage the user to use our system. The aim of our task is to categorize wastes into five classes such as paper, glass, metal, plastic, and trash in an automated system. For our project, we have compared the result of different deep learning algorithms such as DenseNet169, MobileNetV2, ResNet50, VGG19, SVM, CNN, and YOLO v8. We used YOLO v8 for object detection as it gives the best real-time accuracy among all algorithms.  Our system will reduce the segregation cost and speed up the process of waste management. This will also reduce the environmental pollution and people will not be directly contacted with waste because segregation is done by our smart bin.


## TOOLS
software used for our project are given below:
- Google Colab
- Python
- Machine Learning
- Roboflow
- VS studio
- PHP
- C++
  
Hardware used for our project are:
- Camera
- Arduino
- Servo Motor
- Ultrasonic Sensor
- Metal Detector Sensor
- Weight Measurement Sensor
- Capacitive Sensor
- LCD display
- Wi-Fi Shield
- Conveyor Belt
- Bins

## OBJECT DETECTION
In our system object classification is done based on image processing, sensor-based classification, and density-based classification

### <ins>IMAGE CLASSIFICATION</ins>
We have trained our model using CNN, SVM, DenseNet169, MobileNetV2, ResNet50, VGG19, and YOLO v8 algorithms with our datasets and compared the result for best accuracy

| Algorithms  | Accuracy    | Precesion   | Recall     |
| ----------- | ----------- | ----------- | -----------|
| CNN         | 90%         |    0.90     | 0.90       |
| DenseNet169 | 99%         |    0.99     | 0.99       |
| MobileNetV2 | 91%         |    0.92     | 0.91       |
| ResNet50    | 98%         |    0.98     | 0.98       |
| VGG19       | 98%         |    0.98     | 0.98       |
| YOLOv8      | 98%         |    0.96     | 0.95       |
| SVM         | 17%         |    0.18     | 0.17       |



