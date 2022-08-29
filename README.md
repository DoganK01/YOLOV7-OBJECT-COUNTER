# YOLOV7-OBJECT-COUNTER

# How to run Code
!!! All that needs to be done is to delete the detect.py file you downloaded and run the detect_and_count.py file.

- clone the repository:
- `git clone https://github.com/WongKinYiu/yolov7`
- `%cd yolov7`
- `%%bash`
- `wget https://raw.githubusercontent.com/WongKinYiu/yolov7/u5/requirements.txt`  
- `pip install -r requirements.txt`
- `wget -P /content/gdrive/MyDrive/yolov7/weights https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7x.pt`

# Upgrade pip
- `pip install --upgrade pip`
# Using counter example:
- `!python detect_and_count.py --weights /content/yolov7/weights/yolov7x.pt.3 --conf 0.5 --img-size 640 --source YOLOSample.mp4 --no-trace`




# Result:
![image](https://user-images.githubusercontent.com/98788987/187072479-e7dd5277-a0fb-4204-ba00-48a1aa071a4d.png)


# Sample Videos
Sample 1 : https://www.youtube.com/watch?v=d2_-UikpuLc

Sample 2 : https://www.youtube.com/watch?v=dhr5JtKD774
