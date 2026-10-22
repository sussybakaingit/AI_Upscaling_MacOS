AI photo, video Upscaler + denoiser

How to setup:
It works only in MacOS(maybe in linux too)

brew install python@3.12
brew install python-tk@3.12

/opt/homebrew/bin/python3.12 -m venv venv
source venv/bin/activate

python -m pip install --upgrade pip
python -m pip install onnxruntime numpy customtkinter opencv-python-headless Pillow natsort psutil

python QualityScaler.py
