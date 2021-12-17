# Faster-RCNN-Object-Detection-Model (Pytorch)


## Installation and Setup
    # Clone my repo
    git clone https://github.com/xor0x/Faster-RCNN-Object-Detection-Model
    
    # Install the requirements via Pip.
    pip install -r requirements.txt

## The Directory Structure
The following block shows the directory structure that we will use for this project.

    │   config.py
    │   utils.py
    │   datasets.py
    │   inference.py
    │   model.py
    │   train.py
    ├───data
    │   │───test
    │   │───train
    │   │───valid
    ├───detected_images
    │   ├───images
    ├───outputs
    │   ├───best_model.pth
    │   ├───last_model.pth

## Dataset in Pascal VOC XML format

## Run TensorBoard

Start TensorBoard, specifying the root log directory you used above. Argument logdir points to directory where TensorBoard will look to find event files that it can display.      TensorBoard will recursively walk the directory structure rooted at logdir, looking for .*tfevents.* files.

    $ tensorboard --logdir=runs
