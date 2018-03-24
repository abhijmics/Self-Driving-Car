# Self-Driving-Car
# How to simulate a self driving car

![cover](https://user-images.githubusercontent.com/18666200/37863087-16811426-2f7e-11e8-95c6-30f03c4f5836.png)

---
# Overview


---


#### In this project i am going to use Udacity's self driving car simulator as a testbed for training an autonomous car.

---

# Dependencies
You can install all dependencies by running one of the following commands

You need a [anaconda]() or [miniconda]() to use the environment setting.

# Use TensorFlow without GPU
```sh
conda env create -f environments.yml 
```
OR

# Use TensorFlow with GPU

```sh
conda env create -f environment-gpu.yml
```
Or you can manually install the required libraries (see the contents of the environemnt*.yml files) using pip.


# Usage

---

## Run the pretrained model

Start up the Udacity self-driving simulator, choose a scene and press the Autonomous Mode button. Then, run the model as follows:

``` sh
python drive.py model.h5
```


# To train the model

You'll need the data folder which contains the training images.

```sh
     python model.py
```

This will generate a file model-<epoch>.h5 whenever the performance in the epoch is better than the previous best. For example, the first epoch will generate a file called model-000.h5.

# Credits


The credits for this code go to [naokishibuya](https://github.com/naokishibuya). I've merely created a wrapper to get people started.

### Plugins

License
----
 GNU 
 GENERAL PUBLIC LICENSE
 Version 3, 29 June 2007



