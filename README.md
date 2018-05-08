# virtual-mouse-opencv

I have filtered the green colour using appropriate BGR values. Then by using morphological transformation noise is removed. Lastly, these colour values are tracked and mapped accordingly to the mouse pointer using the pynput and tkinter libraries with also implementation of basic mathematics. This also gives access to click and drag gesture(geometry concepts) like in the mouse.

# Core libraries used :

* cv2
* numpy
* pynput
* tkinter

I have made a virtual environment in Pycharm and instaled the above packages/dependencies.

# Video Link :

https://www.youtube.com/watch?v=I4YNPaKfoVo

# Results : 

The output was pretty good in terms of latency and also had less noise. You need to change the thresholds so that it works for your surroundings.<br />

![alt text](https://github.com/hasibzunair/virtual-mouse-opencv/blob/master/results.png)
