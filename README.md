# Miscelaneous-Detection

1. cov19-efnb7-yolov5-pytorch-infer.ipynb : Is the inference notebook being used in the competition
2. siim-cov19-yolov5-train-fold-0.ipynb : Is being used to train yoloV5 on the image level object detection (opacities) task for fold 0 there are 4 similar notebooks for the rest of the folds.
3. siimcovid-pytorch-train-fast.ipynb : Is being used for the study level task of the competition where we need to classify images into 4 labels which are mutually exclusive.
4. siimcovid_pytorch_effv2_AUX.ipynb.ipynb : Is another alternate method i am working on for the study level task, where i am using bounding boxes from image level labels to create masks for study level task and using segmentaion loss as an auxillary loss to reduce overfitting.
5. mmdetection_covid.ipynb : Is being used to train models from mmdetection library for image level object detection task.
6. Effdet[Train][Covid].ipynb : Is being used to train efficient det models for image level object detection task.
