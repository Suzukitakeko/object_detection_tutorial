# object_detection_tutorial
object detection tutorial on raspberry pi
***
# 1. VNC 连接 raspberry pi

# 2. 切换为root用户 并激活虚拟环境(tflite)

> 切换为root用户  
> `su`  
> `密码:`  

> 激活虚拟环境  
> `source /home/pi/tflite/bin/activate`

# 3. cd 到相应的文件夹
> `cd examples-master/lite/example/object_detection/raspberry_pi`  
> `ls -l`  

可以看到：  
```-rw-r--r-- 1 pi ljf    2695 2月  28 22:41 control.py
-rw-r--r-- 1 pi ljf    4363 2月  28 21:53 detect.py
-rw-r--r-- 1 pi ljf 4447793 2月  27 09:05 detect.tflite
-rw-r--r-- 1 pi ljf    5311 3月   1 08:43 detect_traffic.py
-rw-r--r-- 1 pi ljf 4448941 2月  27 20:23 detect_traffic.tflite
-rw-r--r-- 1 pi ljf   11210 2月  28 22:31 object_detector.py
-rw-r--r-- 1 pi ljf    6344 2月  26 21:31 object_detector_test.py
drwxr-xr-x 2 pi ljf    4096 2月  28 22:41 __pycache__
-rw-r--r-- 1 pi ljf    3784 2月  26 21:31 README.md
-rw-r--r-- 1 pi ljf     147 2月  26 21:31 requirements.txt
-rw-r--r-- 1 pi ljf     702 2月  26 21:31 setup.sh
drwxr-xr-x 2 pi ljf    4096 2月  26 21:31 test_data
```
输入命令  
`python detect_traffic.py --model=detect_traffic.tflite`

