# Gym-tools-Modeling

This repository contains the research and modeling notebooks for the Gym Tools Classification project. The project aims to classify gym tools based on images using CNN. The model used in this project is a pre-trained VGG16 model with additional layers for classification.
To download the trained model, please click [here]([link-to-download-model](https://drive.google.com/drive/folders/1UwIH6epKdSkBNr84h3S6yltNk1BjCSKD?usp=sharing)).
This model was trained on our dataset that we stored on [Kaggle]([link-to-your-dataset](https://bit.ly/C23-PC637-Dataset)).

| Information       | Value                                               |
|-------------------|-----------------------------------------------------|
| Model structure   | Pre Trained VGG16, MaxPooling2D, Flatten, Dense, Dense (softmax) |
| Model input       | Image that already converted to array with rescale 1./255 |
| Model output      | Softmax values [0, 1, 2, ..., 9]                    |
