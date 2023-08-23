# Self-supervised machine learning application on breast cancer
This is my machine learning application developed for my master's degree project and dissertation. This project focuses on creating and training models using self-supervised learning techniques (SimCLR, SwAV, DINOv2) with a fine-tuning layer, using the BreakHis dataset for breast histopathology image classification.


## Project Aim
This project aims to demonstrate the power of transfer learning in self-supervised learning

## Dataset
The breast histopathology images were downloaded from the offical site https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/.</br>
I had reorganised the dataset into 8 different folders each represents one class for the image classification task. The image data were loaded using the DataModule class provided by PyTorch Lightning, and then splitted into training set, validation set, test set. DataModule also allows changing the batch size of training/validation/test set.

## Model
The three models were built using LightningModule class in PyTorch Lightning.</br>


