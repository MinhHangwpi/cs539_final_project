
# Translating ASL Fingerspelling

## Background
This repository focuses on translating American Sign Language (ASL) fingerspelling into text using deep learning, particularly Long-Short-Term-Memory (LSTM) networks. Voice recognition is prevalent, but gesture-to-text technology is still underdeveloped. ASL native signers are much faster at fingerspelling than typing on a mobile device. The project is based on a [Kaggle competition](https://www.kaggle.com/competitions/asl-fingerspelling) with a 180GB dataset of ASL phrases, normalized using Mediapipes.

## Solution
The project utilizes LSTM networks for processing sequential frames representing ASL phrases. The dataset contains 123 parquet files with labeled ground truth. The files include body, hand, and face coordinates, mapped with coordinates extracted from video frames.

## How to Run
We recommend you run the notebook with the Kaggle environment since the data set is very large, around 180GB and is already hosted on Kaggle.
Open a new Kaggle cloud-based notebook and import this notebook to that environment. Select GPU as the hardware accelerator option. To connect to the data source, In the "Data" section on the right hand side, click on "Add Data" and search the keyword "Google - American Sign Language Fingerspelling Recognition" and click on "add competition".

Alternatively, you can "Copy & Edit" the our notebook at https://www.kaggle.com/code/minhhangr/gompei-ninjas-asl-fingerspelling-with-lstm to get your own copy of our notebook.

## Resources
- [ASL Fingerspelling Recognition w/ TensorFlow](https://www.kaggle.com/code/gusthema/asl-fingerspelling-recognition-w-tensorflow) by Gusthema on Kaggle.
- Long Short-Term Memory Networks With Python: Develop Sequence Prediction Models With Deep Learning by Jason Brownlee.

## Team members
1. Minh-Hang Radetsky
2. Sam Bryan
3. Adish Jain
4. Sireesha Bachu
