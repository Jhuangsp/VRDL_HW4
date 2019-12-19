# VRDL_HW4

## Code
GitHub Link: https://github.com/Jhuangsp/VRDL_HW4
 - `train.py`: Main file used to train the model
 - `eval.py`: Main file used to evaluate the test data
 - `yolact.py`: YOLACT model definition
 - `backbone.py`: Backbone model definition used by YOLACT model
 - `TA_utils.py`: Utils provide by TA, used to convert binary mask to rle format.
 - `data`: Storing dataset, configurations (e.g. data path, model select, iterations...).
 - `layers`: Loss functions definition, output utils, box utils.
 - `utils`: Augmentations, logger, timer..., etc.

## Reference
[dbolya/yolact](https://github.com/dbolya/yolact)
You Only Look At CoefficienTs
A simple, fully convolutional model for real-time instance segmentation.