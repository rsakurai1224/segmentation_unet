# Summary
This repository implements semantic segmentation on Pascal VOC2012 using U-Net.

U-Net is an encoder-decoder model consisted of only convolutions, without fully connected layers.

An article about this implementation is [here](https://qiita.com/tktktks10/items/0f551aea27d2f62ef708).


# Usage
To show how to run.

`python main.py --help`


To run with data augmentation using GPUs.

`python main.py --gpu --augmentation`
