# Text-2-image
Enjoy

### TODO:
- combining with Real-ESRGAN model

# Preview
<br/>
<img src="notebooks/data/image_35.png" width="400">
<img src="notebooks/data/image_4.png" width="400">
<br/>
<img src="notebooks/data/image_17.png" width="400">
<img src="notebooks/data/image_24.png" width="400">


# Super-resolution
Low resolution
<br/>
<img src="notebooks/highres/image00low.jpg" width="400">

High resolution
<br/>
<img src="notebooks/highres/image00high.jpg" width="400">


## Prerequisite
- install miniforge
- create virtual env
- pip install jupyter
- pip install min-dalle
- then pip uninstall torch (comes with min-dalle)
- pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu113


## Credits
- Min-Dalle (Generating Arty images)
  - https://github.com/kuprel/min-dalle
- Real-ESRGAN (Image and video restoration)
  - https://github.com/xinntao/Real-ESRGAN
