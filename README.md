# object_detection_android

An AI android app which uses camera to detects  80 different objects in real-time using openCV and neural networks.
The application is designed for API level 23, (or Marshmallow) and is compatible with almost 96% of 
devices available in the market. 
To run the app, a folder called 'dnns' must be created on 
the internal storage on the phone and 2 files "yolov3-tiny.cfg" 
and "yolov3-tiny.weights" must be placed in the folder. 
The model is called 'Yolo' which is trained seperately 
and obtained from the Darknet repository. Codes are commented for better understanding. 


# list of the object :
"a person", "a bicycle", "a motorbike", 
"an airplane", "a bus", "a train", "a truck", 
"a boat", "a traffic light", "a fire hydrant",
"a stop sign", "a parking meter", "a car", 
"a bench", "a bird", "a cat", "a dog", "a horse", 
"a sheep", "a cow", "an elephant", "a bear", 
"a zebra", "a giraffe", "a backpack", "an umbrella", 
"a handbag", "a tie", "a suitcase", "a frisbee", "skis", 
"a snowboard", "a sports ball", "a kite", "a baseball bat", 
"a baseball glove", "a skateboard", "a surfboard",
"a tennis racket", "a bottle", "a wine glass", "a cup", 
"a fork", "a knife", "a spoon", "a bowl", "a banana", 
"an apple", "a sandwich", "an orange", "broccoli", 
"a carrot", "a hot dog", "a pizza", "a doughnut", "a cake", 
"a chair", "a sofa", "a potted plant", "a bed", "a dining table", 
"a toilet", "a TV monitor", "a laptop", "a computer mouse", 
"a remote control", "a keyboard", "a cell phone", "a microwave", 
"an oven", "a toaster", "a sink", "a refrigerator", "a book", 
"a clock", "a vase", "a pair of scissors", "a teddy bear", 
"a hair drier", "a toothbrush"
