
## This code is a fork of https://github.com/eriklindernoren/PyTorch-YOLOv3. Here, this repo is modified to incorporate tracking of detected elements and output an OD-data format CSV.

## Installation
    $ sudo pip3 install -r requirements.txt



## Run 
    To procduce a file you need to use the script ``` dectect.py``` as it follows: 
    $ python3 detect.py --image_folder data/samples/

The tracking rely on the hypothesis that images in your folder names are incremental (or at least sorted).
