# YOLOv5 Improvements

## Introduction

This repository contains code for evaluating the performance improvements made to the YOLOv5 model. The modifications were made to enhance object detection accuracy and generalization capabilities.

## Execution

To execute the code and evaluate the performance of the YOLOv5 model with improvements, run the `Evaluate_performance_Yolov5s_improvments.ipynb` Notebook.

## Modifications

To apply the improvements, you need to modify the `yolov5s.yaml` file with the relevant options provided in the repository.

## Folder Structure

The repository includes diffrent folders, while each of them contains:
- `results`: Contains the results obtained after evaluating the YOLOv5 model with improvements.
- `weights`: Holds the weights of the models with applied modifications.

## Configuration

The `config.yaml` file contains the necessary paths to the train, validation, and test sets, as well as information about the objects being detected.

## Instructions

1. Update the `yolov5s.yaml` file with the desired improvement options.
2. Execute the `Evaluate_performance_Yolov5s_improvments.ipynb` notebook to evaluate the model's performance.
3. The results will be stored in the `results` folder, and the model weights will be saved in the `weights` folder.
4. If you execute a yaml file that contain Dropout, you need also to ajust the code in 'yolo.py' - Add 

By following these instructions, you can explore and assess the impact of the applied improvements on the YOLOv5 model's object detection performance.
