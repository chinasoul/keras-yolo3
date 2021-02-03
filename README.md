forked from https://github.com/qqwweee/keras-yolo3

my env:  
$ python3 -V  
Python 3.7.3  
$ pip3 show tensorflow|grep -i version  
Version: 2.4.0  
$ pip3 show keras|grep -i version  
Version: 2.4.3

```
wget https://pjreddie.com/media/files/yolov3.weights
python3 convert.py yolov3.cfg yolov3.weights model_data/yolo.h5
python3 yolo_video.py --image
```
<img src="https://github.com/chinasoul/keras-yolo3/blob/master/result.jpg" width="600"/><br/>
