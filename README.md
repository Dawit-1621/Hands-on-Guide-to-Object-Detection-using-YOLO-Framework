## Hands on Guide to Object Detection suing YOLO framework
The YOLO framework (You Only Look Once).
It takes the entire image in a single instance and predicts the bounding box coordinates and class probabilities for these boxes. The biggest advantage of using YOLO is its superb speed – it’s incredibly fast and can process 45 frames per second. YOLO also understands generalized object representation.
<br>
YOLO algorithm employs convolutional neural networks (CNN) to detect objects in real-time. 
## Installation
- Clone darkent from GitHub </br>
!git clone https://github.com/AlexeyAB/darknet
- Download pre-trained YOLOv4 weights
!wget https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v3_optimal/yolov4.weights

## How does the YOLO Framework Function?
YOLO first takes an input image:<br>
https://cdn.analyticsvidhya.com/wp-content/uploads/2018/12/Screenshot-from-2018-11-15-17-43-42.png![image](https://user-images.githubusercontent.com/23136710/162576455-7f23dcda-12a5-495e-b2a8-174608ecceda.png)
<br>
The framework then divides the input image into grids (say a 3 X 3 grid):<br>
https://cdn.analyticsvidhya.com/wp-content/uploads/2018/12/Screenshot-from-2018-11-15-17-46-32.png![image](https://user-images.githubusercontent.com/23136710/162576524-db6a22ad-e54e-45a3-9cdd-299dfa1bceea.png)

<br>
Image classification and localization are applied on each grid. YOLO then predicts the bounding boxes and their corresponding class probabilities for objects
## Porject Descriptions 

## Licensing, Authors, Acknowledgements


