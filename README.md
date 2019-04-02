#basically a change to https://github.com/mans-men/eye-blink-detection-demo to allow reddit scrolling with blinking, and redundancy to allow head movement (using multiple monitors, because why not)

## Environment
* win10
* python 3.7
* opencv 4.*
* imutils
* dlib
* Anaconda3

## install packages
```
conda intall dlib
conda install opencv3
pip install imutils
pip install scipy
```

## sample 
open the terminal 
```
python detect_blinks.py
```

```
python detect_blinks.py -h
optional arguments:
  -h, --help            show this help message and exit
  -p SHAPE_PREDICTOR, --shape-predictor SHAPE_PREDICTOR
                        path to facial landmark predictor
  -v VIDEO, --video VIDEO
                        path to input video file
  -a THRESHOLD, --maximum THRESHOLD
                        threshold to determine closed eyes
  -i THRESHOLD, --minimum THRESHOLD
                        threshold to determine closed eyes
  -f FRAMES, --frames FRAMES
                        the number of consecutive frames the eye must be below
                        the threshold
```

##Pending more work to support multiple windows and aditional features