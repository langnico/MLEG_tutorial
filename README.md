# Tutorial: Machine Learning for Environmental and Geosciences (MLEG)

This tutorial is split into two practical parts. 

1) **ML_intro** provides an introduction to classical Machine Learning approaches with sklearn.
 
2) **DL_tutorial** introduces convolutional neural networks (CNNs) with keras and tensorflow.

## Getting Started

Clone this repository to your local machine with:

```
git clone https://github.com/langnico/MLEG_tutorial.git
```

Download the required data for the "DL_tutorial" from this link:

> https://drive.google.com/open?id=1KoR9ISddhHsecsZG0lmePNONYKOZns1E

Move the directories into the `DL_tutorial/` directory. The directory tree should look like this:

* DL_tutorial/
	* data/
	* model_weights/
	* pretrained_models_imageNet/


## Prerequisites

We are going to write and execute the code in a jupyter notebook. The DL_tutorial will use keras with a tensorflow backend. 

Therefore, we need to install:

* python3
* jupyter
* tensorflow

Further we will need the python packages/modules:

* sklearn
* numpy
* matplotlib
* pandas
* keras


## Installing
We propose to install python via anaconda.
1) [Install Anaconda](https://docs.anaconda.com/anaconda/install/) and read the [Anaconda tutorial (20min)](https://conda.io/docs/user-guide/getting-started.html)

2) Create a new environment: ```conda create --name MLEGenv python=3.6```
3) Activate the new environment
    * Windows: ```activate MLEGenv```
    * Linux and macOS: ```source activate MLEGenv```
    
    --> now your terminal prompt should start with ***(MLEGenv)*** 
4) Install the following packages in your activated MLEGenv:
    
    ```
    conda install jupyter
    conda install scikit-learn
    conda install pandas
    conda install matplotlib
    conda install keras
    ```
    
5) Install tensorflow following the:
[official installation instructions](https://www.tensorflow.org/install/)


## Verify your installation
1. In the activated MLEGenv type ```which python```. This should point to the python installation in your conda env e.g. ```/anaconda3/envs/DL_tutorial/bin/python```

2. Open a terminal and go to the location of the file: `installation_check.ipynb`

    Then open the jupyter notebook with: ```jupyter notebook installation_check.ipynb```

    NOTE: If this does not automatically open a browser showing the notebook, then open a browser (Firefox, Chrome) and type: `http://localhost:8889/notebooks/installation_check.ipynb`
    
    Then select the first cell containing the imports and click on the `> Run` Button.
    If your installation was successful, the output should be like this:
    
    ```
    Using TensorFlow backend.
    successfully imported
    keras version:  2.2.4
    ```

## Code inspirations

* https://github.com/tgjeon/Keras-Tutorials
* https://github.com/flyyufelix/cnn_finetune

## Authors
* Riccardo De Lutio
* Mikhail Usvyatsov
* Nico Lang 







