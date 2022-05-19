# Auto-detection Biased Language

This project purpose to detect biased text by developing a deep learning model using sentences or Edited text from Wikipedia

This repo was tested with python 3.8.13

These commands will create and install packages from requirements
```
$ python3 -m venv bias_tagger
$ source bias_tagger/bin/activate
$ pip install -r requirements.txt

```

## Overview

`create_dataset/`: Code for making the dataset. It works by crawling and filtering Wikipedia for bias-driven edits.

`train_model/`: Code for training models and using trained models.
