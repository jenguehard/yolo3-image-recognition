"# yolo3-image-recognition" 

This repo allows you to use YOLOV3 image recognition and captionning algorithms on custom images and videos.

In order for it to work you need to download pre-trained yolov3 weights from this link : https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v3_optimal/yolov3.weights 

The downloaded file needs to be put into the yolo-coco directory.

Here is an example of the command line to use the python file : 

python yolo_video.py --input videos/airport.mp4 --output output/airport_output.avi --yolo yolo-coco
