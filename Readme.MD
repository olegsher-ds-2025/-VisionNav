# How to install YOLO on raspberry pi 

```sudo apt-get update && sudo apt-get install ffmpeg libsm6 libxext6  -y
sudo apt install python3-pip -y
pip install -U pip
mkdir work
cd work/
python3 -m venv .venv
. .venv/bin/activate
pip install ultralytics
sudo reboot```

cd work/
. .venv/bin/activate
vi 1.py

from ultralytics import YOLO

#Load a YOLOv8n PyTorch model
model = YOLO("yolov8n.pt")
#Export the model to NCNN format
model.export(format="ncnn")  # creates 'yolov8n_ncnn_model'
#Load the exported NCNN model
ncnn_model = YOLO("yolov8n_ncnn_model")
#Run inference
results = ncnn_model("https://ultralytics.com/images/bus.jpg")

python3 1.py
