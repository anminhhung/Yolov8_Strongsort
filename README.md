# yolov8 & tracking

### Setup
```
pip3 install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu116
pip3 install -r requirements.txt
```

Install torchvision from the source
```
git clone https://github.com/pytorch/vision
cd vision
python setup.py install
```

Download yolov8 model [link](https://github.com/ultralytics/ultralytics)

### Run code
```
python3 yolo/v8/detect/pipeline.py --source video.mp4 --reid-weights osnet_x0_25_market1501.pt --show-vid 
```

Output Video Save at "runs" dir