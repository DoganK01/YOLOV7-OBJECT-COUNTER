# YOLOV7-OBJECT-COUNTER

# How to run Code


- clone the repository:
- `git clone https://github.com/DoganK01/YOLOV7-OBJECT-COUNTER`
- `%cd content/YOLOV7-OBJECT-COUNTER/yolov7-main`
- `%%bash`
- `wget https://raw.githubusercontent.com/WongKinYiu/yolov7/u5/requirements.txt`  
- `pip install -r requirements.txt`
- `wget -P /content/YOLOV7-OBJECT-COUNTER/yolov7-main/weights https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7x.pt`

# Upgrade pip
- `pip install --upgrade pip`
# Using counter example:
- For Object Counter 1:
- `!python detect.py --weights /content/YOLOV7-OBJECT-COUNTER/yolov7-main/weights/yolov7x.pt --conf 0.5 --img-size 640 --source YOLOSample.mp4 --no-trace`

- For Object Counter 2:
- `!python detect_and_count.py --weights /content/YOLOV7-OBJECT-COUNTER/yolov7-main/weights/yolov7x.pt --conf 0.5 --img-size 640 --source YOLOSample.mp4 --no-trace`


# Result:
## detect.py (Object Counter 1)
![image](https://user-images.githubusercontent.com/98788987/187072479-e7dd5277-a0fb-4204-ba00-48a1aa071a4d.png)
## detect_and_count.py (Object Counter 2) (This code is without red lines)


https://user-images.githubusercontent.com/98788987/233976913-dddafc05-baac-4226-ac20-ed452e003a2b.mp4



# Sample Videos
Sample 1 : https://www.youtube.com/watch?v=d2_-UikpuLc

Sample 2 : https://www.youtube.com/watch?v=dhr5JtKD774
