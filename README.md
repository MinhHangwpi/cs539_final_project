
# Translating ASL Fingerspelling

## Background
This repository focuses on translating American Sign Language (ASL) fingerspelling into text using deep learning, particularly Long-Short-Term-Memory (LSTM) networks. Voice recognition is prevalent, but gesture-to-text technology is still underdeveloped. ASL native signers are much faster at fingerspelling than typing on a mobile device. The project is based on a [Kaggle competition](https://www.kaggle.com/competitions/asl-fingerspelling) with a 180GB dataset of ASL phrases, normalized using Mediapipes.

## Solution
The project utilizes LSTM networks for processing sequential frames representing ASL phrases. The dataset contains 123 parquet files with labeled ground truth. The files include body, hand, and face coordinates, mapped with coordinates extracted from video frames.

## How to Run

Load the notebook to Kaggle Cloud environment and run there. Since the dataset is substantial, with a size of 180GB, and is hosted on Kaggle, it is preferable to run there to take advantage of the provided GPU as a hardware accelerator.

## Resources
- [ASL Fingerspelling Recognition w/ TensorFlow](https://www.kaggle.com/code/gusthema/asl-fingerspelling-recognition-w-tensorflow) by Gusthema on Kaggle.
- Long Short-Term Memory Networks With Python: Develop Sequence Prediction Models With Deep Learning by Jason Brownlee.

## Team members
1. Minh-Hang Radetsky
2. Sam Bryan
3. Adish Jain
4. Sireesha Bachu
