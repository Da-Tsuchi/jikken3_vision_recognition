# VGG Model Training and Evaluation

This repository provides tools for training and evaluating VGG models. It includes scripts to train VGG models on a specific dataset and then evaluate/test the model.

## Table of Contents

1. [Setup](#setup)
2. [Usage](#usage)

## Setup 

**Note:** This is only for GPU
1. Create Python 3.10 Environment
```bash
conda create -n [environment name] python=3.10 -y
conda activate [environment name]
```
2. Clone this repository.

```bash
git clone https://github.com/Da-Tsuchi/jikken3_vision_recognition.git
cd jikken3_vision_recognition
```

3. Install required packages.

```bash
pip install -r requirements.txt
```

## Usage

1. Place your data in the appropriate directory.
2. Train and test the model.

```bash
python main.py
```

3. (Optional) Only test the model.

```bash
cd src
python test.py
```

4. Do online demo

**Note:** This is only for jetson.

Access to [jetson_camera_demo](https://github.com/Da-Tsuchi/VGG_Demo.git)

## Author and Acknowledgements
This project was made possible thanks to the vision and efforts of **Shiryu Ueno**. We are grateful for their outstanding contributions.

