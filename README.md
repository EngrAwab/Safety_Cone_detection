# Safety_Cone_detection
Safety Cone Detection using Yolov8 models as well optimize .onxx and .blob model
This is the already trained model for cone detection you can deploy this model on mnay devices and it porvides real time detection.It also conatians .blob models which is the motpized version using oepnvino tool kit so you can use it in OAK-D devices.


# How to use?
You can use this model my just using CLI version of yolov8 
```
yolo predict model=Cone.pt source='path-to-video'
```

# Requiremnts 
```
pip install ultralytics
```
