# SMTrack

Official code for "SMTrack: End-to-End Trained Spiking Neural Networks for Multi-Object Tracking in RGB Videos", IOT-J, 2026
  - https://ieeexplore.ieee.org/abstract/document/11381993

## Environment
Developed in python3.8 

  ```
  cd SMTrack
  conda create -n SMTrack python=3.8
  conda activate SMTrack
  pip install --upgrade pip
  cd YOLOX
  pip install -r requirements.txt && python setup.py develop

  ```
## Prepare
**1. Downlodad datasets**
  - MOT17: https://motchallenge.net/data/MOT17.zip
  - MOT20: https://motchallenge.net/data/MOT20.zip
  - DanceTrack: https://dancetrack.github.io/
  - BEE24: https://holmescao.github.io/datasets/BEE24

<br />

**2. Locate codes and datasets as below**
```
-Train
 -python run/mot20_train.sh
 -python run/mot17_train.sh
 -python run/dancetrack_train.sh
 -python run/bee_train.sh


- workspace
  - code
    - 1. YOLOX
    - 2. FastReID
    - 3. Tracker
  - dataset
    - MOT17
    - MOT20
    - DanceTrack
    - Bee24
```

<br />

**3. Run**
```
run 1. YOLOX
run 2. FastReID
run 3. Tracker
```

