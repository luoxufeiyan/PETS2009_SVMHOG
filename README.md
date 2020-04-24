# PETS2009_SVMHOG

Pedestrian tracking using  SVM + HOG method, KCF and CSRT tracker implemented. 

## Start

### SVM+HOG

To start with, change `VIDEO_PATH` as the source video input, `OUTPUT_PATH` for masked video output. You may need pedestrian dataset as training set for SVM model.

Code is compatible for both local environment and Google Colab. 


### KCF

Change `video_path` to your image frames.


### Convert frames to video

combine output frames to MP4 video file.

Eg: using 12 framerate.

`ffmpeg -framerate 12 -i 000%03d.jpg output.mp4`

## Output

![](https://pic.luoxufeiyan.com/uploads/20200424163243.png)

