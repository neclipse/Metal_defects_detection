# Metal_defects_detection

## Coworkers: 
Hao Wen

## Objective: 
Defects dection in SEM images by using advanced computer vision, Mask-RCNN

## Tool:
It adopts the Detectron2 as the main Engine. 

## The basic workflow:

1. Convert dataset to COCO format
2. Register the dataset with Detectron
3. Check the dataset
4. Train on the dataset with carefully selected model from the [model zoo](https://github.com/facebookresearch/detectron2/blob/master/MODEL_ZOO.md). Tune the model if necessary.
5. Validate the dataset with model inference and evaluation
