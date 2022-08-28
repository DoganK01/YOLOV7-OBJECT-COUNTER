# YOLOV7-OBJECT-COUNTER
Object Counting with the newest yolov7
- Count all objetcs by classes and works perfetcly on every image or on a video
- Code can run on Both (CPU & GPU)
- Video/WebCam/External Camera/IP Stream Supported

# Steps to run Code

- clone the repository:
- `git clone https://github.com/WongKinYiu/yolov7`
- %cd yolov7
- `%%bash`
- `wget https://raw.githubusercontent.com/WongKinYiu/yolov7/u5/requirements.txt`
- `wget -P /content/gdrive/MyDrive/yolov7/weights https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7x.pt`
-  ``
- `pip install -r requirements.txt`
# Upgrade pip with mentioned command below.
- `pip install --upgrade pip`
# Using counter example:
- `!python detect.py --weights /content/gdrive/MyDrive/yolov7/weights/yolov7x.pt.3 --conf 0.5 --img-size 640 --source YOLOSample.mp4 --no-trace`




# Result:
![image](https://user-images.githubusercontent.com/98788987/187072479-e7dd5277-a0fb-4204-ba00-48a1aa071a4d.png)



Sample 1 : https://www.youtube.com/watch?v=d2_-UikpuLc

Sample 2 : https://www.youtube.com/watch?v=dhr5JtKD774
