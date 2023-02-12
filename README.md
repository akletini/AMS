# This repository was used for model creation in AMS

It is not meant for running any of the notebooks but rather documents the work done in the project.

- DetectionDatasetConversion.ipynb was used to convert the German Traffic Sign Detection Benchmark data to YOLO format
- TF_model_maker.ipynb was used to convert the GTSDB data to a suitable format for EfficientDet-Lite0 and to train said model
- Yolov7.ipynb was used for training the YOLO model and shows the attempts made to convert it to a Tensorflow-Lite format
- The subdirectory CNNmodelcreation contains the files used for training and creating the CNN used for labeling detected traffic signs
