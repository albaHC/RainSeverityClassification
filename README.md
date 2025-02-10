# RainSeverityClassification

This repository presents the source code related to the [paper](https://arxiv.org/abs/2407.12663) "Albanese, Andrea, et al. "Is That Rain? Understanding Effects on Visual Odometry Performance for Autonomous UAVs and Efficient DNN-based Rain Classification at the Edge." arXiv preprint arXiv:2407.12663 (2024)." The paper presents the study and analysis through laboratory experiments of the effect of rainy conditions during UAV missions. The experimental setup is detailed in the paper.

This repository permits to train and test a rain severity classificator with this [dataset](https://ieee-dataport.org/documents/adverse-rainy-conditions-autonomous-uavs). The dataset consists of around 335K real images equally distributed among 7 classes. The classes represent different levels of rain intensity, namely "Clear", "Slanting Heavy Rain", "Vertical Heavy Rain", "Slanting Medium Rain", "Vertical Medium Rain", "Slanting Low Rain", and "Vertical Low Rain". The dataset has been acquired during laboratory experiments and simulates a low-altitude flight. The dataset is publicy available in IEEE Dataport.

The notebook "train.ipynb" trains MobileNetV2 and MobileNetV3 small.

The notebook "trainSqueeze.ipynb" trains Squeezenet.

The three models are provided in tflite format.
