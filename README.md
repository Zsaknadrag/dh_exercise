# dh_exercise
Presentation and solution of the task can be found at *vanda_balogh_exercise_conf.ipynb* 
The notebook is organized to subsections which are in line with the specific points of the task.

The output is organized as the following:
```
results
├── batch_size
├── cr_reports
├── history
├── learning_rate
└── plots
```
where
- *plots* contain train-val comparison of losses and metrics
- *cr_reports* include classification reports (precision, recall, f1score) on train and test sets
- *history* contains the output of the training
- *learning_rate* and *batch_size* are directoris dedicated to optimization strategies surveying the performance of different learning rates and batch sizes on EfficientNetB0
- the prefix of each file indicates the name of the backbone model deployed (baseline=EfficientNetB4, EfficientNetB0, MobileNetV2, ResNet50)


Details:
- environment: google colab
- DL framework: tf keras
