# License-Plate-Detection

Requirements:
1. [Mask R-CNN](https://github.com/matterport/Mask_RCNN)(Clone the repo)
2. [mask_rcnn_coco.h5](https://github.com/matterport/Mask_RCNN/releases)

## To run:
#Train a new model starting from pre-trained COCO weights

python3 custom.py train --dataset=/path/to/datasetfolder --weights=coco

#To check validation, use inspect_custom_model.ipynb

## Test results

