# License-Plate-Detection

Requirements:
1. [Mask R-CNN](https://github.com/matterport/Mask_RCNN)(Clone the repo)
2. [mask_rcnn_coco.h5](https://github.com/matterport/Mask_RCNN/releases)

## To run:
Train a new model starting from pre-trained COCO weights
```
python3 custom.py train --dataset=/path/to/datasetfolder --weights=coco
```
Use inspect_custom_model.ipynb to check custom images

## Test results:
![alt text](https://github.com/tanmaypandey7/License-Plate-Detection/blob/master/test%20results/1_true_plate.JPG "Original plate")
![alt text](https://github.com/tanmaypandey7/License-Plate-Detection/blob/master/test%20results/1_detected_plate.png "Detected plate")

![alt text](https://github.com/tanmaypandey7/License-Plate-Detection/blob/master/test%20results/2_true_plate.jpeg "Original plate")
![alt text](https://github.com/tanmaypandey7/License-Plate-Detection/blob/master/test%20results/2_detected_plate.png "Detected plate")

![alt text](https://github.com/tanmaypandey7/License-Plate-Detection/blob/master/test%20results/3_true_plate.jpeg "Original plate")
![alt text](https://github.com/tanmaypandey7/License-Plate-Detection/blob/master/test%20results/3_detected_plate.png "Detected plate")
