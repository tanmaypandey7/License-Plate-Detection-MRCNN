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
![alt text](https://github.com/tanmaypandey7/License-Plate-Detection/blob/master/test%20results/true%20plate.JPG "Original plate")
![alt text](https://github.com/tanmaypandey7/License-Plate-Detection/blob/master/test%20results/detected%20plate.png "Detected plate")

![alt text](https://github.com/tanmaypandey7/License-Plate-Detection/blob/master/test%20results/true%20plate%202.jpeg "Original plate")
![alt text](https://github.com/tanmaypandey7/License-Plate-Detection/blob/master/test%20results/detected%20plate%202.png "Detected plate")

![alt text](https://github.com/tanmaypandey7/License-Plate-Detection/blob/master/test%20results/true%20plate%203.jpeg "Original plate")
![alt text](https://github.com/tanmaypandey7/License-Plate-Detection/blob/master/test%20results/detected%20plate%203.png "Detected plate")
