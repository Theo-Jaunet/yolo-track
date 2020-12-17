This code is a fork of https://github.com/eriklindernoren/PyTorch-YOLOv3. Here, this repo is modified to incorporate tracking of detected elements and output an OD-data formatted CSV.

## Installation
Clone this repo, and install the requierements (you may want to use a virtual pip env for that). 
For faster computation of model's inferences, you can install CUDA.
    
    $ sudo pip install -r requirements.txt 


## Run 
For the tracking, need to use the script ``` dectect.py``` as it follows: 

    $ python3 detect.py --image_folder data/samples/
    
Any folder can be used, ``` data/samples/ ``` is simply the default.

The tracking rely on the hypothesis that images in your folder names are incremental (or at least sorted).
